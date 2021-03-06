## Glossary

### Agile/Lean UX Glossary

#### Analysis and Design {#AnalysisAndDesign}

Analysis and Design.

#### Business Model {#BusinessModel}

Business Model definition.

#### Feature List {#FeatureList}

Feature List definition.

### Content Model Glossary

#### Content Attribute {#ContentAttribute}

Content Type field data type

#### Content Audit

Documents that allow you to review page-by-page how content is performing against predefined measures of quality and effectiveness.

#### Content Inventory (#ContentInventory)

A Content Inventory is an internal list of content items, filterable by business goals and audience interests and goals. The objective is to prioritize content items by their value in order to decide what to keep and what to discard.

#### Content Item {#ContentItem}

An instantiation of a Content Type. In the case of a Node.js Mongoose implementation, this would be a document forming part of a collection.

#### Content Model {#ContentModel}

A Collection of Content Types

#### Content Type {#ContentType}

A Collection of Content Attributes

#### COPE {#Cope}

["Create Once and Publish Everywhere"](https://www.programmableweb.com/news/cope-create-once-publish-everywhere/2009/10/13), dating back to the NPR Structure Content implementations of 2009.

### Architecture Glossary

#### Mongoose Schema {#MongooseSchema}

> Each schema maps to a MongoDB collection and defines the shape of the documents within that collection.
> Each key in our blogSchema defines a property in our documents which will be cast to its associated SchemaType. For example, we've defined a title which will be cast to the String SchemaType and date which will be cast to a Date SchemaType. Keys may also be assigned nested objects containing further key/type definitions (e.g. the `meta` property above). See [Schemas in the Mongoose Documentation](http://mongoosejs.com/docs/guide.html)

#### Mongoose SchemaType {#MongooseSchemaType}

Following are all valid SchemaTypes.

* String
* Number
* Date
* Boolean
* Array
    * Of SchemaTypes
* Objectid
    * The primary key for a referenced Collection of Documents
* Mixed
    * An anything goes, "non-schema" schema type
* Buffer
    * Useually used for binary data "blobs"

#### SCS {#SCS}

Structured Content Server

\pagebreak
