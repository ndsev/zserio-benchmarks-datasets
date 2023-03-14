# Zserio Datasets

Data sets for zserio benchmarks. This repository contains mocked data in JSON format needed to run
[Zserio Benchmarks](https://github.com/ndsev/zserio/tree/master/benchmarks) and
[Protobuf Benchmarks by Zserio](https://github.com/ndsev/zserio-protobuf-benchmarks).

> Most of the datasets are created by [Mockaroo](https://mockaroo.com/).

Each folder can contain several datasets which are JSON files with the `*.json` extension.
When Mockaroo was used for dataset generation, then the corresponding Mockaroo schema is included with the
`*.schema.json` extension - e.g. `addressbook` contains the dataset `addressbook.json` and it's Mockaroo schema
`adressbook.schema.json`.

When a dataset is not compatible between zserio and protobuf, then two JSON files with extra
`*.zs.json` and `*.proto.json` extensions can be used - e.g. `apollo` contains the dataset `apollo.proto.json`
for protobuf and slightly modified `apollo.zs.json` for zserio.
