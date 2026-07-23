---
created: <% tp.date.now("DD-MM-YYYY") %>
tags:
  - daily_note
workout done:
weight:
---
- [ ] Steps 7500
- [ ] [[DoC|Daily Stretching]] | https://www.youtube.com/watch?v=m9gMzFngyxY
- [ ] Dancing 10min

# Food intake

#### Frühstück
#food [[Holy_Energy]] 1pc
#food [[6K_Protein_Nougat_Choc_Nut]] 40g

#### Mittag
#food [[]] 500g


#### Abend
#food [[]] 500g


#### Snacks
#food [[]] 500g

# Workout
burns 40/1000 steps
#workout 

[Dance](https://www.youtube.com/watch?v=H-QVJpZn8bw)

# Body Mindfulness
### Isolation Upper Body
-  Chest
	- Forwards
	- Backwards
- Ripcage
	- Forwards
	- Backwards
	- Sideways
### Isolation Lower Body
- Hips
	- Left
	- Right
	- Forwards
	- Backwards
# Workout Program
[[Programs/Gym/Workout v.1/Program v.1|Program v.1]]
<%* 
const day = await tp.date.now("dddd") 
let template_use = ""
switch (day) {
	case "Monday":
		template_use = tp.file.include("[[Workout Upper 1]]");
		break;
	case "Tuesday":
		template_use = tp.file.include("[[Workout Legs 1]]");
		break;
	case "Thursday":
		template_use = tp.file.include("[[Workout Upper 2]]");
		break;
	case "Friday":
		template_use = tp.file.include("[[Workout Legs 2]]");
		break;
	default:
		template_use = ""
		break;
}
-%>
<% template_use %>


# Goals
<%*
const targetDate = moment("2026-08-31", "YYYY-MM-DD");
const now = moment();
const daysLeft = targetDate.diff(now, 'days');
%>
<% daysLeft %> Tage übrig:
- 105kg
- Front splits
- Jede woche tanzen
- Bridge progression
- Needle?


# TODOs
- create different routines
	- Small
	- Standard
	- Expanded
	- https://www.daniwinksflexibility.com/bendy-blog/getting-a-pointier-toe-pointe
	- https://www.youtube.com/watch?v=ZCxVt_ABxJI
	- https://www.youtube.com/watch?v=BsvDc-d6lO8
	- https://www.youtube.com/shorts/8brCzOZv_WM