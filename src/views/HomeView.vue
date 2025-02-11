<script setup lang="ts">
import { ref } from "vue";

const schedule = ref([
  {
    day: "Понеділок",
    lessons: [
      { group: "AB", subject: "" },
      {
        group: "AB",
        subjects: [
          { name: "None", teacher: "" },

          {
            name: "Database developement та трьохланкові застосунки",
            teacher: "Давиденко Є.О.,доц",
						link: "http://meet.google.com/cat-tnso-ydp",
          },
        ],
      },
      {
        group: "AB",
        subjects: [
          {
            name: "Комп'ютерні мережі",
            teacher: "Журавська І.М.,проф",
						link: " https://meet.google.com/iyv-nkyo-uxj",
          },
        ],
      },
      {
        group: "AB",
        subjects: [
          {
            name: "Професійна практика програмної інженерії",
            teacher: "Кандиба І.О.,ст.викл",
						link: "https://meet.google.com/wau-wiwx-rsq",
          },
          { name: "None", teacher: "" },
        ],
      },
      { group: "AB", subject: "" },
    ],
  },

  {
    day: "Вівторок",
    lessons: [
      {
        group: "AB",
        subjects: [
          {
            name: "Якість програмного забезпечення та тестування",
            teacher: "викл. Бондаренко С.В.",
						link: "https://meet.google.com/waf-ajkc-ydu",
          },
        ],
      },
      {
        group: "AB",
        subjects: [
          {
            name: "Інвестиційний менеджмент",
            teacher: "Черненок К.П., доц",
						link: "https://us04web.zoom.us/j/4605528245?pwd=QnNTblFiYnFhQStZSmF6SVo4WnhKQT09",
          },
          {
            name: "Розробка адаптивних web-інтерфейсів",
            teacher: "викл. Стоєв Є.Д.",
						link: "https://meet.google.com/czq-ofrv-xar",
          },
        ],
      },
      {
        group: "AB",
        subjects: [
          {
            name: "Інвестиційний менеджмент",
            teacher: "Черненок К.П., доц",
						link: "https://us04web.zoom.us/j/4605528245?pwd=QnNTblFiYnFhQStZSmF6SVo4WnhKQT09",
          },
          {
            name: "Основи криміналістики",
            teacher: "Казарян Е.Г.,ст.викл",
            link: "https://us05web.zoom.us/j/83231578709?pwd=RUdzVnVTNWxlRnJLaElQVEpVMDBHdz09",
          },
        ],
      },
      {
        group: "AB",
        subjects: [
          {
            name: "None",
            teacher: "",
            link: "",
          },
          {
            name: "Основи криміналістики",
            teacher: "Казарян Е.Г.,ст.викл",
            link: "https://us05web.zoom.us/j/83231578709?pwd=RUdzVnVTNWxlRnJLaElQVEpVMDBHdz09",
          },
        ],
      },
      { group: "AB", subject: "" },
    ],
  },

  {
    day: "Середа",
    lessons: [
      { group: "A", subject: "", group2: "Б", subject2: "" },
      { group: "A", subject: "", group2: "Б", subject2: "" },
			 {
				group: "А",
				subjects: [
					{
						name: "Іноземна мова (англійська)",
						teacher: "Буровицька Ю.М.,ст.викл",
						link: "https://us04web.zoom.us/j/8862508048?pwd=0VyHahbAenpXOGDaqBVG7p9yOOeYcv.1",
					},
				],
			group2: "Б", subject2: "" },

      {
        group: "A",
        subjects: [
          {
            name: "Database developement та трьохланкові застосунки",
            teacher: "викл. Бондаренко С.В.",
						audit: "10-214",
						link: "https://meet.google.com/waf-ajkc-ydu",
          },
        ],
        group2: "Б",
        subjects2: [
          {
            name: "Розробка адаптивних web-інтерфейсів",
            teacher: "викл. Стоєв Є.Д.",
						audit: "10-307",
						link: "https://meet.google.com/czq-ofrv-xar",
          },
        ],
      },
      {
        group: "A",
        subjects: [
          {
            name: "Розробка адаптивних web-інтерфейсів",
            teacher: "викл. Стоєв Є.Д.",
						audit: "2-308",
						link: "https://meet.google.com/czq-ofrv-xar",
          },
        ],
        group2: "Б",
        subjects2: [
          {
            name: "Database developement та трьохланкові застосунки",
            teacher: "викл. Бондаренко С.В.",
						audit: "2-309",
						link: "https://meet.google.com/waf-ajkc-ydu",
          },
        ],
      },
    ],
  },
  {
    day: "Четвер",
    lessons: [
      {
        group: "A",
        subjects: [
          {
            name: "Database developement та трьохланкові застосунки",
            teacher: "викл. Бондаренко С.В.",
						audit: "11-206",
						link: "https://meet.google.com/waf-ajkc-ydu",
          },
          {
            name: "Розробка адаптивних web-інтерфейсів",
            teacher: "викл. Стоєв Є.Д.",
						audit: "11-206",
						link: "https://meet.google.com/czq-ofrv-xar",
          },
        ],
        group2: "Б",
        subjects2: [
          {
            name: "Розробка адаптивних web-інтерфейсів",
            teacher: "викл. Стоєв Є.Д.",
						audit: "2-306",
						link: "https://meet.google.com/czq-ofrv-xar",
          },
          {
            name: "Database developement та трьохланкові застосунки",
            teacher: "викл. Бондаренко С.В.",
						audit: "2-306",
						link: "https://meet.google.com/waf-ajkc-ydu",
          },
        ],
      },
      {
        group: "A",
        subjects: [
          {
            name: "Якість програмного забезпечення та тестування",
            teacher: "викл. Бондаренко С.В.",
						audit: "11-206",
						link: "https://meet.google.com/waf-ajkc-ydu",
          },
        ],
        group2: "Б",
        subjects2: [
          {
            name: "Іноземна мова (англійська)",
            teacher: "Агєєва-Каркашадзе В.О.,доцент б.в.з.",
						audit: "11-106",
						link: "https://us04web.zoom.us/j/8848681680?pwd=eXJRRDN3Nk1JclBIRlRrMmRhWUxtQT09",
          },
        ],
      },
      {
        group: "",
        subject: "",

        group2: "Б",
        subjects2: [
          {
            name: "Якість програмного забезпечення та тестування",
            teacher: "викл. Бондаренко С.В.",
						audit:"2-309",
						link: "https://meet.google.com/waf-ajkc-ydu",
          },
        ],
      },
      {
        group: "",
        subject: "",

        group2: "Б",
        subjects2: [
          {
            name: "Професійна практика програмної інженерії",
            teacher: "Кандиба І.О.,ст.викл",
						audit: "10-214",
						link: "https://meet.google.com/wau-wiwx-rsq",
          },
					{
						name: "None",
						teacher: "",
						link: "",
					},
        ],
      },
      { group: "AB", subject: "" },
    ],
  },

  {
    day: "Пятниця",
    lessons: [
      {
        group: "А",
        subjects: [
          {
            name: "None",
            teacher: "",
            link: "",
          },
          {
            name: "Професійна практика програмної інженерії",
            teacher: "Бондаренко С.В.,викл",
						audit: "1-403А",
						link: "https://meet.google.com/waf-ajkc-ydu",
          },
        ],

        group2: "Б",
        subjects2: [
          {
            name: "",
            teacher: "",
          },
        ],
      },
      {
        group: "А",
        subjects: [
          {
            name: "Професійна практика програмної інженерії",
            teacher: "Бондаренко С.В.,викл",
						audit: "10-308",
						link: "https://meet.google.com/waf-ajkc-ydu",
          },
        ],

        group2: "Б",
        subjects2: [
          {
            name: "Комп'ютерні мережі",
						teacher: "ст. викл. Тогоєв О.Р.",
						audit: "2-509",
						link: "https://meet.google.com/mus-negh-piv",
          },
        ],
      },
      {
        group: "А",
        subjects: [
          {
            name: "Комп'ютерні мережі",
            teacher: "Савінов В.Ю.,доц",
						audit: "1-009а",
						link: "https://meet.google.com/mus-negh-piv",
          },
        ],

        group2: "Б",
        subjects2: [
          {
            name: "Професійна практика програмної інженерії",
            teacher: "Кандиба І.О.,ст.викл",
						audit: "10-307",
						link: "https://meet.google.com/wau-wiwx-rsq",
          },
        ],
      },
      { group: "AB", subject: "" },
			{ group: "AB", subject: "" },

    ],
  },
]);

const hasContent = (lesson: any) => {
  return (
    lesson.subjects?.some(
      (subject: any) => subject.name && subject.name !== "None"
    ) ||
    (lesson.subject && lesson.subject !== "")
  );
};
</script>

<template>
  <div class="rozklad">
    <table class="table1">
      <tr>
        <th>День</th>
        <th>Пара</th>
        <th>Підгрупа А</th>
        <th>Підгрупа Б</th>
      </tr>
      <template v-for="(day, dayIndex) in schedule" :key="dayIndex">
        <tr
          v-for="(lesson, lessonIndex) in day.lessons"
          :key="`${dayIndex}-${lessonIndex}`"
          :class="{ 'day-dark': ['Понеділок', 'Вівторок'].includes(day.day) }"
        >
          <td v-if="lessonIndex === 0" :rowspan="day.lessons.length">
            {{ day.day }}
          </td>
          <td>{{ lessonIndex + 1 }}</td>
          <td
            :class="{ combined: lesson.group === 'AB' && hasContent(lesson) }"
            :colspan="lesson.group === 'AB' ? 2 : 1"
          >
            <template v-if="lesson.subjects">
              <div
                v-for="(subject, index) in lesson.subjects"
                :key="index"
                class="subject-cell"
              >
                <div class="audit" v-if="subject.audit">{{ subject.audit }}</div>
                <div>
                  <a v-if="subject.link" :href="subject.link" target="_blank">
                    {{ subject.name !== "None" ? subject.name : " " }}
                  </a>
                  <span v-else>{{ subject.name !== "None" ? subject.name : " " }}</span>
                </div>
                <div class="teacher">{{ subject.teacher }}</div>
              </div>
            </template>
            <div v-else-if="lesson.teacher">
              <div>{{ lesson.subject }}</div>
              <div class="teacher">{{ lesson.teacher }}</div>
            </div>
            <div v-else>{{ lesson.subject }}</div>
          </td>
          <td v-if="lesson.group !== 'AB'">
            <template v-if="lesson.subjects2">
              <div
                v-for="(subject, index) in lesson.subjects2"
                :key="index"
                class="subject-cell"
              >
                <div class="audit" v-if="subject.audit">{{ subject.audit }}</div>
                <div>
                  <a v-if="subject.link" :href="subject.link" target="_blank">
                    {{ subject.name !== "None" ? subject.name : " " }}
                  </a>
                  <span v-else>{{ subject.name !== "None" ? subject.name : " " }}</span>
                </div>
                <div class="teacher">{{ subject.teacher }}</div>
              </div>
            </template>
            <div v-else>{{ lesson.subject2 }}</div>
          </td>
        </tr>
      </template>
    </table>
  </div>
</template>

<style scoped>
.rozklad {
	color: white;
	display: flex;
	justify-content: center;
	margin-bottom: 100px;
}

table,
th,
td {
	border: 1px solid rgba(255, 255, 255, 0.1);
	border-collapse: collapse;
}

.table1 {
  text-align: center;
  width: 80%;
  background-color: transparent;
  border-radius: 8px;
  overflow: hidden;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

td {
  background-color: #1e1e1e;
  padding: 12px;
  transition: background-color 0.3s ease;
}

.day-dark td {
  background-color: #2d2d2d;
}

td:first-child {
  font-weight: 600;
}

td:nth-child(2) {
  font-weight: 500;
}

.combined {
  color: white;
}

th {
	background-color: #079950;
	color: white;
	padding: 15px;
	font-weight: 600;
}

.subject-cell {
	padding: 8px 0;
	transition: background-color 0.3s ease;
	min-height: 3.5em;
	display: flex;
	flex-direction: column;
	justify-content: center;
	position: relative;
}

.subject-cell:not(:last-child) {
	border-bottom: 1px solid rgba(255, 255, 255, 0.1);
}

.subject-cell:hover {
	background-color: #2a2a2a;
}

.teacher {
	font-size: 0.8em;
	color: #a0a0a0;
	margin-top: 4px;
}

.audit {
  position: absolute;
  top: 2px;
  right: 5px;
  color: #079950;
  font-size: 0.8em;
  font-weight: 500;
}

.subject-cell > div:not(.audit) {
  margin: 2px 0;
}

@media (max-width: 600px) {
	.rozklad td {
		font-size: 11px;
		padding: 6px;
	}

	.rozklad th {
		font-size: 12px;
		padding: 8px;
	}

	.subject-cell {
		padding: 4px 0;
	}

	.teacher {
		font-size: 9px;
	}

  .audit {
    font-size: 8px;
    top: 1px;
    right: 2px;
  }
}
</style>
