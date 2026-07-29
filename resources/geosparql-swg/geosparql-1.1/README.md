# GeoSPARQL 1.1

This directory contains the RDF resources for [GeosPARQL 1.1](http://www.opengis.net/doc/IS/geosparql/1.1) as loaded into the OGC's [Definitions Service](https://defs.opengis.net/).

## Use

The resources are organised and (will be) synchronised using [PrezManifest](https://github.com/Kurrawong/prezmanifest) which is a tool that reads repository content and loads it into an RDF DB.

PrezManifest reads the `manifest.ttl` file, discovers the resources linked to from there, validates them and then synchronises them with a target RDF DB via _Graph Store Protocol_ commands like this:

```bash
pm sync manifest.ttl
```

## Contact

For all issues to do with these resources, please contact the GeoSPARQL SWG at via [details on its main repo](https://github.com/opengeospatial/ogc-geosparql/#contact).
