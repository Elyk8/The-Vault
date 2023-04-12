## <% moment(tp.file.title,'YYYY-MM-DD').format("dddd, DD MMMM YYYY") %>
[[<% tp.date.now("YYYY-MM-DD", -1, tp.file.title, "YYYY-MM-DD") %>|Yesterday]] <-> [[<% tp.date.now("YYYY-MM-DD", 1, tp.file.title, "YYYY-MM-DD") %>|Tomorrow]]
Week:: [[<%moment(tp.file.title).format("gggg-[W]ww")%>]]
## Journal
- <% tp.file.cursor(0) %>
