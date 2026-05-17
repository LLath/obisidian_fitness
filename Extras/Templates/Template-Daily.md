---
created: <% tp.date.now("DD-MM-YYYY") %>
tags:
  - daily_note
workout done:
weight:
---
- [ ] Steps 7500
- [ ] [[DoC|Daily Stretching]]
- [ ] Dancing 10min

# Food intake

#### Frühstück
#food [[Holy_Energy]] 500ml


#### Mittag
#food [[]] 500g


#### Abend
#food [[]] 500g


#### Snacks
#food [[]] 500g

# Workout
burns 40/1000 steps
#workout 

# Workout Program
[[Program v.1]]
<%* 
const day = await tp.date.now("dddd") 
let template_use = ""
switch (day) {
	case "Tuesday":
		template_use = tp.file.include("[[Workout Day 1]]");
		break;
	case "Thursday":
		template_use = tp.file.include("[[Workout Day 2]]");
		break;
	case "Friday":
		template_use = tp.file.include("[[Workout Day 3]]");
		break;
	case "Sunday":
		template_use = tp.file.include("[[Workout Day 4]]");
		break;
	default:
		template_use = ""
		break;
}
-%>
<% template_use %>


# Goals
<%*
const targetDate = moment("2026-06-30", "YYYY-MM-DD");
const now = moment();
const daysLeft = targetDate.diff(now, 'days');
%>
<% daysLeft %> Tage übrig:
- 115kg
- Bridge? [Dani Winks progression](https://www.daniwinksflexibility.com/bendy-blog/the-ultimate-bridge-pose-progression-guide)
- https://www.strongrfastr.com/de/1800-kalorien-vegan-ernaehrungsplan