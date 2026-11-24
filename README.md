# berthplan

Weekly berth plans for Port Berth terminal. Each plan is a JSON file in `plans/`
listing the lifts scheduled for one vessel call.

Every plan is checked against the gantry load envelope in CI using the
`vicjustine/gantry-envelope-action` custom Action.
