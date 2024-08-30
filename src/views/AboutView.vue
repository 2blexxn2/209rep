<template>
  <div class="about">
    <div class="container">
      <div class="teachers-list">
        <div v-for="teacher in teachers" :key="teacher.name" class="teacher-card">
          <h3>{{ teacher.name }}</h3>
          <p v-if="teacher.telegram">
            Telegram: <a :href="`https://t.me/${teacher.telegram}`">@{{ teacher.telegram }}</a>
          </p>
          <p>
            Email: <a :href="`mailto:${teacher.email}`">{{ teacher.email }}</a>
          </p>
          <p>Курси: {{ teacher.courses }}</p>
          <div v-if="teacher.links && teacher.links.length">
            <p>Посилання:</p>
            <ul>
              <li v-for="(link, index) in teacher.links" :key="index">
                <a :href="link.url">{{ link.text }}</a>
              </li>
            </ul>
          </div>
          <p v-if="teacher.consultations">Консультації: {{ teacher.consultations }}</p>
        </div>
      </div>
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
          name: "Кірей Катерина Олександрівн��",
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
}

.container {
  max-width: 1200px;
  margin: 0 auto;
}

.teachers-list {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
  gap: 20px;
}

.teacher-card {
  background-color: #111111;
  border: 1px solid #ffffff0f;
  padding: 20px;
  border-radius: 8px;
}

.teacher-card h3 {
  color: rgb(7, 153, 80);
  margin-top: 0;
}

.teacher-card p {
  margin: 10px 0;
}

.teacher-card ul {
  padding-left: 20px;
}

a {
  color: rgb(7, 153, 80);
  text-decoration: none;
}

a:hover {
  text-decoration: underline;
}

@media (max-width: 768px) {
  .teachers-list {
    grid-template-columns: 1fr;
  }
}
</style>
