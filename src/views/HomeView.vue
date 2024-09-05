<script setup lang="ts">
import { ref } from "vue";

const schedule = ref([
	{
		day: "Понеділок",
		lessons: [
			{
				group: "AB",
				subjects: [
					{
						name: "Розробка програмного забезпечення для ОС Android",
						teacher: "викл. Раленко В.С.",
						link: "https://meet.google.com/fhu-hdbz-xcm",
					},
					{
						name: "Web development",
						teacher: "викл. Раленко В.С.",
						link: "https://meet.google.com/fhu-hdbz-xcm",

					},
				],
			},
			{
				group: "AB",
				subjects: [
					{
						name: "Операційні системи",
						teacher: "доц. Горбань Г.В.",
						link: "https://meet.google.com/ntv-xafm-imh"
					}
				],
			},
			{
				group: "AB",
				subjects: [
					{
						name: "Розробка web-застосунків на базі ASP.NET",
						teacher: "викл. Стоєв Є.Д.",
						link: "https://meet.google.com/czq-ofrv-xar"
					},
					{ name: "None", teacher: "" },
				],
			},
			{ group: "AB", subject: "" },
			{ group: "AB", subject: "" },
		],
	},

	{
		day: "Вівторок",
		lessons: [
			{
				group: "A",
				subjects: [
					{
						name: "ASP.NET",
						teacher: "викл. Стоєв Є.Д. (ауд. 2-309)",
						link: "https://meet.google.com/czq-ofrv-xar"

					},
				],
			},
			{
				group: "A",
				subjects: [
					{
						name: "ASP.NET",
						teacher: "викл. Стоєв Є.Д. (ауд. 2-309)",
						link: "https://meet.google.com/czq-ofrv-xar"

					},
				],
			},
			{
				group: "A",
				subjects: [
					{
						name: "Web development",
						teacher: "викл. Раленко В. С. (ауд. 1-313)",
						link: "https://meet.google.com/fhu-hdbz-xcm",

					},
				],
				group2: "Б",
				subjects2: [
					{
						name: "Web development",
						teacher: "викл. Стоєв Є.Д. (ауд. 2-309)",
						link: "https://meet.google.com/czq-ofrv-xar"


					},
					{
						name: "ОС",
						teacher: "доц. Кірей К.О (ауд. 1-009)",
						link: "https://meet.google.com/tno-kqsg-nro"
					},
				],
			},
			{
				group: "A",
				subjects: [
					{
						name: "ОС",
						teacher: "доц. Горбань Г.В (ауд. 1-403А)",
						link: "https://meet.google.com/wby-ccff-xgs"
					},
				],
				group2: "Б",
				subjects2: [
					{
						name: "Web development",
						teacher: "викл.Стоєв Є.Д. (ауд. 2-309)",
						link: "https://meet.google.com/czq-ofrv-xar"

					},
				],
			},
			{
				group2: "Б",
				subjects2: [
					{
						name: "Розробка програмного забезпечення для ОС Android",
						teacher: " викл. Раленко В.С  (ауд. 1-313)",
						link: "https://meet.google.com/fhu-hdbz-xcm",

					},
				],
			},
		],
	},

	{
		day: "Середа",
		lessons: [
			{
				group: "A",
				subjects: [
					{
						name: "Web development",
						teacher: "викл. Раленко В.С. (ауд. 1-403А)",
						link: "https://meet.google.com/fhu-hdbz-xcm",

					},
					{
						name: "ОС",
						teacher: "доц. Горбань Г.В (ауд. 1-404)",
						link: "https://meet.google.com/wby-ccff-xgs"

					},
				],
				group2: "Б",
				subject2: "",
			},

			{
				group: "A",
				subjects: [
					{
						name: "Іноземна мова",
						teacher: "Буровицька Ю.М. (ауд. 11-112)",
						link: "https://us04web.zoom.us/j/8862508048?pwd=0VyHahbAenpXOGDaqBVG7p9yOOeYcv.1"
					},
				],
				group2: "",
				subject2: "",
			},

			{
				group: "",
				subject: "",

				group2: "Б",
				subjects2: [
					{
						name: "Іноземна мова",
						teacher: "Агєєва-Каркашадзе В.О (ауд. 11-112)",
					},
				],
			},
			{
				group2: "Б",
				subjects2: [
					{
						name: "Розробка програмного забезпечення для ОС Android",
						teacher: "викл. Раленко В.С (ауд. 1-404)",
						link: "https://meet.google.com/fhu-hdbz-xcm",

					},
				],
			},
			{ group: "A", subject: "", group2: "Б", subject2: "" },
		],
	},
	{
		day: "Четвер",
		lessons: [
			{
				group: "AB",
				subjects: [
					{
						name: "Практичні заняття: Арт-терапія (2 підгрупа)",
						teacher: "доц. Кузнецова О.А. (ауд. 10-301)",
						link: ""
					}
				],
			},
			{
				group: "AB",
				subjects: [{
					name: "Практичні заняття: Психологія переговорів",
					teacher: "Габро І.В. (ауд. 10-301)",
					link: ""
				},
				{
					name: "Лекційні заняття: Арт-терапія доц. Кузнецова О.А./ Фін-тех і криптовалюти викл. Решетник Ю.В. / Психологія переговорів Габро І.В."
				}]
			},
			{
				group: "AB",
				subjects: [
					{
						name: "Практичні заняття:Арт-терапія доц. Кузнецова О.А. (ауд. 10-301) / Фін-тех і криптовалюти викл. Решетник Ю.В.(1 підгрупа) ауд. 1-108",
						teacher: "",
					},
					{ name: "None", teacher: "" },
				],
			},
			{ group: "AB", subject: "" },
			{ group: "AB", subject: "" },
		],
	},

	{
		day: "Пятниця",
		lessons: [
			{
				group: "",
				subject: "",

				group2: "Б",
				subjects2: [
					{
						name: "",
						teacher: "",
					},
				],
			},
			{
				group2: "Б",
				subjects2: [
					{
						name: "ASP.NET",
						teacher: "викл. Стоєв Є.Д. (ауд. 10-214)",
						link: "https://meet.google.com/czq-ofrv-xar"

					},
				],
			},
			{
				group2: "B",
				subjects2: [
					{
						name: "ASP.NET",
						teacher: "викл. Стоєв Є.Д. (ауд. 10-214)",
						link: "https://meet.google.com/czq-ofrv-xar"

					},
				],
			},
			{
				group: "А",
				subjects: [
					{
						name: "Розробка програмного забезпечення для ОС Android",
						teacher: "викл. Раленко В.С (ауд. 2-309)",
						link: "https://meet.google.com/fhu-hdbz-xcm",

					},
				],

				group2: "Б",
				subjects2: [
					{
						name: "ОС",
						teacher: "доц. Кірей К.О (ауд. 1-009)",
						link: "https://meet.google.com/tno-kqsg-nro"

					},
				],
			},

			{
				group: "A",
				subjects: [
					{
						name: "Розробка програмного забезпечення для ОС Android",
						teacher: "викл. Раленко В.С (ауд. 2-309)",
						link: "https://meet.google.com/fhu-hdbz-xcm",

					},
				],
			},
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
				<tr v-for="(lesson, lessonIndex) in day.lessons" :key="`${dayIndex}-${lessonIndex}`">
					<td v-if="lessonIndex === 0" :rowspan="day.lessons.length">
						{{ day.day }}
					</td>
					<td>{{ lessonIndex + 1 }}</td>
					<td :class="{ combined: lesson.group === 'AB' && hasContent(lesson) }"
						:colspan="lesson.group === 'AB' ? 2 : 1">
						<template v-if="lesson.subjects">
							<div v-for="(subject, index) in lesson.subjects" :key="index" class="subject-cell">
								<div>
									<a v-if="subject.link" :href="subject.link" target="_blank">
										{{ subject.name }}
									</a>
									<span v-else>{{ subject.name }}</span>
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
							<div v-for="(subject, index) in lesson.subjects2" :key="index" class="subject-cell">
								<div>
									<a v-if="subject.link" :href="subject.link" target="_blank">
										{{ subject.name }}
									</a>
									<span v-else>{{ subject.name }}</span>
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
	margin-bottom: 500px;
}

table,
th,
td {
	border: 1px solid rgb(255, 255, 255);
	border-collapse: collapse;
}

.table1 {
	text-align: center;
	width: 80%;
}

td {
	padding: 5px;
}

.combined {
	background-color: #2c3e50;
	color: white;
}

.subject-cell {
	padding: 5px 0;
}

.subject-cell:not(:last-child) {
	border-bottom: 1px solid white;
}

.teacher {
	font-size: 0.8em;
	color: #abaaaa;
}

@media (max-width: 600px) {
	.rozklad td {
		font-size: 8px;
		padding: 2px;
	}

	.rozklad th {
		font-size: 10px;
	}

	.rozklad tr {
		font-size: 7px;
	}

	.subject-cell {
		padding: 2px 0;
	}

	.teacher {
		font-size: 6px;
	}
}
</style>
