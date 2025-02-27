# Survey Form Project Guidelines

## Objective
Build an app that is functionally similar to [this survey form](https://survey-form.freecodecamp.rocks). **Do not copy this demo project.**

## User Stories

1. You should have a page title in an `h1` element with an `id` of `title`.
2. You should have a short explanation in a `p` element with an `id` of `description`.
3. You should have a `form` element with an `id` of `survey-form`.
4. Inside the `form` element:
   1. You are required to enter your name in an `input` field that has an `id` of `name` and a `type` of `text`.
   2. You are required to enter your email in an `input` field that has an `id` of `email`.
   3. If you enter an incorrectly formatted email, you will see an HTML5 validation error.
   4. You can enter a number in an `input` field that has an `id` of `number`.
   5. The number input should not accept non-numeric values.
   6. If you enter numbers outside the defined `min` and `max` range, you will see an HTML5 validation error.
   7. For the name, email, and number input fields:
      1. You should see corresponding `label` elements describing the purpose of each field with the following `id`s: `id="name-label"`, `id="email-label"`, and `id="number-label"`.
      2. Each field should have a placeholder text providing instructions.
   8. You should have a `select` dropdown element with an `id` of `dropdown` and at least two options.
   9. You can select an option from a group of at least two radio buttons grouped using the `name` attribute.
   10. You can select several fields from a series of checkboxes, each with a `value` attribute.
   11. You should have a `textarea` for additional comments.
   12. You should have a `button` with an `id` of `submit` to submit all the inputs.

## Completion Criteria

1. Fulfill all user stories and pass all the required tests.
2. Personalize the design with your own styling.
3. Link your CSS file by adding the following line in your HTML:
   ```html
   <link rel="stylesheet" href="styles.css">
   ```


