<template>
  <div class="about">
    <div class="container">
      <table class="rozklad">
        <thead>
          <tr>
            <th>Ім'я</th>
            <th>Telegram</th>
            <th>Email</th>
            <th>Курси</th>
            <th>Посилання</th>
            <th>Консультації</th>
          </tr>
        </thead>
        <tbody>
          <tr v-for="teacher in teachers" :key="teacher.name">
            <td>{{ teacher.name }}</td>
            <td>
              <a
                v-if="teacher.telegram"
                :href="`https://t.me/${teacher.telegram}`"
                >@{{ teacher.telegram }}</a
              >
            </td>
            <td>
              <a :href="`mailto:${teacher.email}`">{{ teacher.email }}</a>
            </td>
            <td>{{ teacher.courses }}</td>
            <td>
              <template v-if="teacher.links">
                <div v-for="(link, index) in teacher.links" :key="index">
                  <a :href="link.url">{{ link.text }}</a>
                </div>
              </template>
            </td>
            <td>{{ teacher.consultations }}</td>
          </tr>
        </tbody>
      </table>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      teachers: [
        {
          name: "Антіпова Катерина Олександрівна",
          telegram: "KaterynaAntipova",
          email: "antipova.katerina@chmnu.edu.ua",
          courses: "ОБД, ООП",
          links: [
            {
              text: "Особисте посилання",
              url: "https://meet.google.com/rou-etmu-yrx",
            },
          ],
          consultations: "",
        },

        {
          name: "Боровльова Світлана Юріївна",
          telegram: "BSU1952",
          email: "svetlya1952@gmail.com",
          courses: "Мова програмування Python",
          links: [
            {
              text: "Особисте посилання",
              url: "https://meet.google.com/yjv-qxit-wfx",
            },
          ],
          consultations: "",
        },

        {
          name: "Буровицька Юлія Миколаївна",
          telegram: "yuliiia11",
          email: "uliy2005@gmail.com",
          courses: "Іноземна мова",
          links: [],
          consultations: "",
        },

        {
          name: "Горбань Гліб Валентинович",
          telegram: "gleb_gorban",
          email: "hlib.horban@chmnu.edu.ua",
					courses: "ООП, Операційні системи",
          links: [
            {
              text: "Особисте посилання",
              url: "https://meet.google.com/ahw-vvsv-syi",
            },
          ],
          consultations: "",
        },

        {
          name: "Давиденко Євген Олександрович",
          telegram: "DavydenkoYevhen",
          email: "davydenko@chmnu.edu.ua",
          courses: "SPA",
          links: [
            {
              text: "Особисте посилання",
              url: "https://meet.google.com/cat-tnso-ydp",
            },
          ],
          consultations: "",
        },

        {
          name: "Кандиба Ігор Олександрович",
          telegram: "KandybaIhor",
          email: "ihor.kandyba@chmnu.edu.ua",
          courses: "Мова програмування Python",
          links: [
            {
              text: "Особисте посилання",
              url: "https://meet.google.com/wau-wiwx-rsq",
            },
          ],
          consultations: "",
        },

        {
          name: "Кірей Катерина Олександрівна",
          telegram: "asd0987655",
          email: "kateryna.kirey@chmnu.edu.ua",
					courses: "ОБД, Операційні системи",
          links: [
            {
              text: "Особисте посилання",
              url: "https://meet.google.com/kjc-mmiz-mhk",
            },
          ],
          consultations: "",
        },

        {
          name: "Раленко Віктор Сергійович",
          telegram: "RalenkoVictor",
          email: "ralenko.v@chmnu.edu.ua  ",
					courses: "Web development, Розробка програмного забезпечення для ОС Android",
          links: [{ text: "Особисте посилання", url: "" }],
          consultations: "",
        },

        {
          name: "Стоєв Євгеній Дмитрович",
          telegram: "stoievyevhenii",
          email: "stoiev.yevhenii@chmnu.edu.ua",
					courses: "ASP.NET, Web development",
          links: [{ text: "Особисте посилання", url: "" }],
          consultations: "",
        },

        {
          name: "Швед Альона Володимирівна",
          telegram: "",
          email: "avshved@chmnu.edu.ua",
          courses: "Емпіричні методи програмної інженерії",
          links: [
            {
              text: "Особисте посилання",
              url: "https://meet.google.com/aye-qiwa-naq",
            },
          ],
          consultations: "",
        },

        {
          name: "Шерстюк Людмила Валеріївна",
          telegram: "l1udmy1a",
          email: "lvsherstiuk@gmail.com",
          courses: "Іноземна мова (англійська)",
          links: [],
          consultations: "",
        },
      ],
    };
  },
};
</script>

<style scoped>
.about {
  font-family: Arial, sans-serif;
  padding: 20px;
  margin-bottom: 500px;
}

.container {
  max-width: 1200px;
  margin: 0 auto;
}

.rozklad {
  width: 100%;
  border-collapse: collapse;
  background-color: #000000;
  box-shadow: 0 0 20px rgba(0, 0, 0, 0.1);
}

.rozklad th,
.rozklad td {
  padding: 12px;
  text-align: left;
  border-bottom: 1px solid #ddd;
}

.rozklad th {
  background-color: rgb(7, 153, 80);
  color: white;
  font-weight: bold;
}

.rozklad tr:nth-child(even) {
  background-color: #000000;
}

.rozklad tr:hover {
  background-color: #000000;
}

a {
  color: rgb(7, 153, 80);
  text-decoration: none;
}

a:hover {
  text-decoration: underline;
}

@media (max-width: 768px) {
  .rozklad {
    font-size: 14px;
  }

  .rozklad th,
  .rozklad td {
    padding: 8px;
  }
}

@media (max-width: 480px) {
  .rozklad {
    font-size: 12px;
  }

  .rozklad th,
  .rozklad td {
    padding: 6px;
  }
}
</style>
