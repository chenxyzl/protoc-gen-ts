# Protoc Gen Typescript

Generates appropriate Protocol Buffer sources from Proto files directly through _TypeScript Compiler API_.

This plugin generates plain **Typescript** files that can be used AMD, UMD, CommonJS module systems.

**See examples folder**

Aim of this protoc plugin is to make usage of protocol buffers easy in Javascript/Typescript by taking modern approaches.

## Key Differences

This protoc plugin does generate fields as **getter** **setters**.

## Roadmap

- <s>Support for repeated non-integer fields</s>
- <s>Generate appropriate service code that is usable with node **grpc** package.</s>
- Make services strongly typed.
- Support `map<TYPE, TYPE>` types as EcmaScript `Map`s.
- Support for `import` directive.
- Support for creating protocol buffer messages directly from their constructors with an object.
