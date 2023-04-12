# Using APA citation style

To use APA citation style, include the `apacite` package as:

```latex
\includepackage[natbibapa]{apacite}
```

Then include the bibliography as:

```latex
\bibliographystyle{apacite}
\bibliography{ref}
```

```{warning}
Do not use the package `cite` in combination with `apacite`, as this will screw things up.
```