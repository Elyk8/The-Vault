# <%moment(tp.file.title).startOf('isoWeek').format("MMM DD")%> - <%moment(tp.file.title).endOf('isoWeek').format("MMM DD")%>

[[<%moment(tp.file.title).subtract(1,'week').format("gggg-[W]WW")%>|⬅️ Previous Week]] - [[<%moment(tp.file.title).add(1,'week').format("gggg-[W]WW")%>|Next Week ➡️️]]
```dataview
table without id
	link(file.path, dateformat(file.day, "cccc")) AS Day,
	Screen AS "💻",
	Spent AS "💲",
	Water AS "🥛",
	choice(Journal,"✔️","❎") AS "📒",
	choice(Reading,"✔️","❎") AS "👓",
	choice(Cardio,"✔️","❎") AS "🏃",
	choice(Workout,"✔️","❎") AS "🏋️‍♂️"
from [[]]
sort file.name ASC
```