# AMAZON WEB SERVICES

El gigante tecnológico americano, dispone de una línea de negocio llamada AWS o Amazon Web Services, la cual están aprovechando empresas como Netflix, la NASA, o españolas como el FC. Barcelona o Mapfre. 
El servicio se lanzó en el 2006, recoge una serie de servicios integrales que ofrece la empresa Amazon para la computación y almacenamiento en la nube, así como para la gestión de bases de datos y aplicaciones móviles, entre otros servicios de cloud computing, para que las empresas puedan acceder a los mismos de forma eficiente, independientemente de su ubicación o localización.


For more about MyST, see [the MyST Markdown Overview](https://jupyterbook.org/content/myst.html).

## Sample Roles and Directivs

Roles and directives are two of the most powerful tools in Jupyter Book. They
are kind of like functions, but written in a markup language. They both
serve a similar purpose, but **roles are written in one line**, whereas
**directives span many lines**. They both accept different kinds of inputs,
and what they do with those inputs depends on the specific role or directive
that is being called.

Here is a "note" directive:

```{note}
Here is a note
```

It will be rendered in a special box when you build your book.

Here is an inline directive to refer to a document: {doc}`markdown-notebooks`.


## Citations

You can also cite references that are stored in a `bibtex` file. For example,
the following syntax: `` {cite}`holdgraf_evidence_2014` `` will render like
this: {cite}`holdgraf_evidence_2014`.

Moreover, you can insert a bibliography into your page with this syntax:
The `{bibliography}` directive must be used for all the `{cite}` roles to
render properly.
For example, if the references for your book are stored in `references.bib`,
then the bibliography is inserted with:

```{bibliography}
```

## Learn more

This is just a simple starter to get you started.
You can learn a lot more at [jupyterbook.org](https://jupyterbook.org).
