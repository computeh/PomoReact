# PomoReact

A Pomodoro is a study technique used to dedicate an interval of time to study and take a break. The conventional
starting period for this method is 25 minutes to study, with a rewarded 5 minute break. After four completed study sessions, the student is
rewarded with a longer, 15 minute break.

My React project PomoReact allows users to specify study and break periods as well as the cycle between events.

You can find the project here: https://computeh.github.io/PomoReact/

## Components

`PomoSettings` - Receives user input for timer customization then sends it to parent component.

`PomoTimer` - Displays timer information.

`SessionLog` - Displays information about a previously completed study session.

`SessionLogList` - Maps and renders an array of session log data to a list of SessionLog components.

## Hooks

`useInterval` - Updates a callback and delay in ms to calculate a function to perform, `tick()`. If the value
for the delay is not equal to null, the interval will be constantly updated through `useEffect()`.