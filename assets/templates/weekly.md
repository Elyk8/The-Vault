# <%moment(tp.file.title).startOf('isoWeek').format("MMM DD")%> - <%moment(tp.file.title).endOf('isoWeek').format("MMM DD")%>

<%tp.file.title%>

[[<%moment(tp.file.title).subtract(1,'week').format("gggg-[W]WW")%>|⬅️]] - [[<%moment(tp.file.title).add(1,'week').format("gggg-[W]WW")%>|➡️️]]