# Forms

- Handling Forms has 2 ways: Template Driven and Reactive

# Template-Driven Forms

- Has less code setup but difficult for complex operations

## Concepts

- Registering form controls [ngModel (all the html tags that use this must have the “name” attribute)]
- Getting access to Angular-managed Form
  [ngForm: <form #form=”ngForm” (ngSubmit)=”onSubmit(form)”>]
- Extracting user input values
- Validating input from Validation
- Using the Form Validation Status
  [#email="ngModel"]
- Validation Styles
  [Angular assigns built-in class names like "ng-touched", we can use those for styling as shown in css file.]
- Interacting with the underlying Form object in the component
- Updating form values programmatically
