# Pogi Email Templates

Email templates for Pogi developed using MJML
https://mjml.io/documentation/

## View the designs on this GitHub Page
https://bawes.github.io/pogi-email-templates/

## Link to page designs

* [Common emails](./common/README.md)
* [Employer app emails](./employer/README.md)
* [Jobs app emails](./jobs/README.md)

## To compile MJML email template into HTML, run:

```bash
mjml -r confirm-1.mjml -o confirm-1.html
```

or for live updates

```bash
mjml --watch candidate-intro.mjml -o candidate-intro.html
```

## Folder Structure

* `/common` - Emails sent commonly for multiple purposes
* `/jobs` - Emails sent from Jobs app
* `/employer` - Emails sent from Employer app
* `/admin` - Emails sent from Admin app
* `/examples` has examples from other projects
* `/img` has shared images across all emails such as logo
