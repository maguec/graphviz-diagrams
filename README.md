## Diagrams in Graphviz

My archive of icons and processes for develpoing diagrams using GraphViz

To generate button like diagrams [this tool works well](http://www.holshousersoftware.com/glass/)

OSA icons can be [downloaded](http://www.opensecurityarchitecture.org/downloads/13_05_osa_icons_png.zip)

## icon normalization

```
find . -name \*.png -exec mogrify -resize 32x32 {} \;
```

## icons dir

- opensource_apps
- infra_services
- osa_icons
- aws
- service_providers

## examples dir

Contains a few example drawings

## to generate drawings

```
dot -Tpng input.dot > output.png
```

## Examples

(https://raw.githubusercontent.com/maguec/graphviz-diagrams/master/examples/final_infra.png)

(https://raw.githubusercontent.com/maguec/graphviz-diagrams/master/examples/vault_example.png)

