# Ember Components Diagnostic

Record your responses inside the fenced code blocks below each question.

1.  Give an example of a visual hierarchy that could be modeled with components. Explain why each piece might be it's own component.

    ```md
    Build a Pizza! You have 3 crusts representing a template. Each series of toppings per crust is a component.
    ```

1.  What is the command to generate a new component called '`my-map`'?

    ```sh
    ember g compontent my map
    ```

1.  What files are created and/or edited to produce a component, and what are their responsibilities?

    ```md
    the above comand generates a component file, a template, and a test. The component file handles actions, the template renders the componenent and displays a views to the client. The test file assures that it is working properly but I dont know how.
    ```

1.  Suppose you have a component '`my-contact`', which is loaded from
    '`app/contacts/template.hbs`' when visiting the `/contacts` route. What is
    the syntax (code that is written) to render this component inside that template?

    ```html
    {{#each contacts as |contact|}}
      {{contacts/my-contact my-contact=my-contact}}
      {{/each}}
    ```

1.  Each contact has multiple phone numbers. Suppose you also have '`my-phone`'
    nested under '`my-contact`'. What is the code you would write in
    '`app/components/my-contact/template.hbs`' to load the nested component and
    pass it data?

    ```html
    <!-- your response here -->
    ```
