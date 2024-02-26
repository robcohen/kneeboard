# Kneeboard

A collection of aircraft checklists, templates, and documents – used before, during, and after flight.

Forked from rbreslow/kneeboard.

- Contains checklists for 1975 Cessna 182P

## Enter development environment
```
$ nix develop .
```

## Make a PDF and clean up
```
$ cd C182P_checklist
$ latexmk -pdf C182P_checklist.tex
$ latexmk -c C182P_checklist.tex
```