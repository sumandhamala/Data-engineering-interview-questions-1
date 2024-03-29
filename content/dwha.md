## [Main title](../README.md)
### [Interview questions](full.md)


# Data Warehousing Architecture
+ [What is the Main Difference between View and Materialized View?](#What-is-the-Main-Difference-between-View-and-Materialized-Vie)
+ [What is Junk Dimension?](#What-is-Junk-Dimensio)
+ [What is Data Warehouse architecture?](#What-is-Data-Warehouse-architectur)
+ [What is an integrity constraints and what are different types of integrity constraints?](#What-is-an-integrity-constraints-and-what-are-different-types-of-integrity-constraint)
+ [Why is that Data Architect actually monitor and enforce compliance data standards?](#Why-is-that-Data-Architect-actually-monitor-and-enforce-compliance-data-standard)
+ [Explain the different data models that are available in detail?](#Explain-the-different-data-models-that-are-available-in-detai)
+ [Differentiate between dimension and attribute?](#Differentiate-between-dimension-and-attribut)
+ [Differentiate between Oltp and Olap?](#Differentiate-between-Oltp-and-Ola)
+ [What is a Real time Data Warehouse and how is it different from near to Real time Data Warehouse?](#What-is-a-Real-time-Data-Warehouse-and-how-is-it-different-from-near-to-Real-time-Data-Warehous)
+ [What is Type 2 Version Dimension?](#What-is-Type-2-Version-Dimensio)
+ [What are Data Modeling and Data Mining?](#What-are-Data-Modeling-and-Data-Minin)
+ [Where the Data Cube Technology is used?](#Where-the-Data-Cube-Technology-is-use)
+ [How can you implement many relations in Star Schema Model?](#How-can-you-implement-many-relations-in-Star-Schema-Mode)
+ [What is Critical Column?](#What-is-Critical-Colum)
+ [What is the main difference between Star and Snowflake Star Schema and which one is better and why?](#What-is-the-main-difference-between-Star-and-Snowflake-Star-Schema-and-which-one-is-better-and-wh)
+ [What is the difference between Dependent Data Warehouse and Independent Data Warehouse?](#What-is-the-difference-between-Dependent-Data-Warehouse-and-Independent-Data-Warehous)
+ [Which technology should be used for interactive Data Querying across multiple dimensions for a decision making for a Dw?](#Which-technology-should-be-used-for-interactive-Data-Querying-across-multiple-dimensions-for-a-decision-making-for-a-D)
+ [What is Virtual Data Warehousing?](#What-is-Virtual-Data-Warehousin)
+ [What is the difference between Metadata and Data Dictionary?](#What-is-the-difference-between-Metadata-and-Data-Dictionar)
+ [What is the difference between Mapping Parameter and Mapping Variable in Data Warehousing?](#What-is-the-difference-between-Mapping-Parameter-and-Mapping-Variable-in-Data-Warehousin)
+ [Explain the advantages Of Raid 1 and 1/0 And 5 and what type of Raid setup would you put your Tx Logs.](#Explain-the-advantages-Of-Raid-1-and-1/0-And-5-and-what-type-of-Raid-setup-would-you-put-your-Tx-Log)
+ [What are the characteristics of data files?](#What-are-the-characteristics-of-data-file)
+ [What is Rollback Segment?](#What-is-Rollback-Segmen)
+ [What is a Table Space?](#What-is-a-Table-Spac)
+ [What is Database Link?](#What-is-Database-Lin)
+ [What is a Hash Cluster?](#What-is-a-Hash-Cluste)
+ [Describe referential Integrity?](#Describe-referential-Integrit)
+ [What is Schema?](#What-is-Schem)
+ [What is Table?](#What-is-Tabl)
+ [What is a View?](#What-is-a-Vie)
+ [What is an Extent?](#What-is-an-Exten)
+ [What is an Index?](#What-is-an-Inde)
+ [What is an Integrity Constrains?](#What-is-an-Integrity-Constrain)
+ [What are Clusters?](#What-are-Cluster)
+ [What are the different types of Segments?](#What-are-the-different-types-of-Segment)
+ [Explain the Relationship among database and Table Space and Data File?](#Explain-the-Relationship-among-database-and-Table-Space-and-Data-Fil)
+ [What is an Index Segment?](#What-is-an-Index-Segmen)
+ [What are the Referential Actions supported by Foreign Key integrity constraint?](#What-are-the-Referential-Actions-supported-by-Foreign-Key-integrity-constrain)
+ [Do you View contain Data?](#Do-you-View-contain-Dat)
+ [What is the use of Control File?](#What-is-the-use-of-Control-Fil)
+ [Can Objects of the same Schema reside in different Table Spaces?](#Can-Objects-of-the-same-Schema-reside-in-different-Table-Space)
+ [Can a Table Space hold objects from different Schemes?](#Can-a-Table-Space-hold-objects-from-different-Scheme)
+ [Can a View based on another View?](#Can-a-View-based-on-another-Vie)
+ [What is a full Backup?](#What-is-a-full-Backu)
+ [What is Mirrored on line redo Log?](#What-is-Mirrored-on-line-redo-Lo)
+ [What is Partial Backup?](#What-is-Partial-Backu)
+ [What is Restricted Mode of Instance Startup?](#What-is-Restricted-Mode-of-Instance-Startu)
+ [What are the steps involved in Database Shutdown?](#What-are-the-steps-involved-in-Database-Shutdow)
+ [What are the advantages of Operating a Database in archivelog mode over operating it in no Archivelog Mode?](#What-are-the-advantages-of-Operating-a-Database-in-archivelog-mode-over-operating-it-in-no-Archivelog-Mod)
+ [What are the different modes of Mounting a Database with the Parallel Server?](#What-are-the-different-modes-of-Mounting-a-Database-with-the-Parallel-Serve)
+ [Can Full Backup be performed when the Database is Open?](#Can-Full-Backup-be-performed-when-the-Database-is-Ope)
+ [What are the steps involved in instance Recovery?](#What-are-the-steps-involved-in-instance-Recover)
+ [What are the steps involved in Database Startup?](#What-are-the-steps-involved-in-Database-Startu)
+ [Which parameter specified in the Default Storage Clause of create Tablespace cannot be Altered after creating the Table Space?](#Which-parameter-specified-in-the-Default-Storage-Clause-of-create-Tablespace-cannot-be-Altered-after-creating-the-Table-Spac)
+ [What is Online redo Log?](#What-is-Online-redo-Lo)
+ [What is Log Switch?](#What-is-Log-Switc)
+ [What is Dimensional Modelling?](#What-is-Dimensional-Modellin)
+ [What are the difference between snow Flake and Star Schema and what are situations where Snow Flake Schema is better than Star Schema to use and when the opposite is True?](#What-are-the-difference-between-snow-Flake-and-Star-Schema-and-what-are-situations-where-Snow-Flake-Schema-is-better-than-Star-Schema-to-use-and-when-the-opposite-is-Tru)
+ [What is a Cube in Data Warehousing concept?](#What-is-a-Cube-in-Data-Warehousing-concep)
+ [What are the differences between Star and Snowflake Schema?](#What-are-the-differences-between-Star-and-Snowflake-Schem)
+ [What are Data Marts?](#What-are-Data-Mart)
+ [What is the Data Type of the Surrogate Key?](#What-is-the-Data-Type-of-the-Surrogate-Ke)
+ [What are Fact and Dimension and Measure?](#What-are-Fact-and-Dimension-and-Measur)
+ [What are the different Types of Data Warehousing?](#What-are-the-different-Types-of-Data-Warehousin)
+ [What do you mean by Static and Local Variable?](#What-do-you-mean-by-Static-and-Local-Variabl)
+ [What is a Source Qualifier?](#What-is-a-Source-Qualifie)
+ [What are the Steps to Build the Data Warehouse?](#What-are-the-Steps-to-Build-the-Data-Warehous)
+ [What is the advantages Data Mining over Traditional approaches?](#What-is-the-advantages-Data-Mining-over-Traditional-approache)
+ [What is the difference between View and Materialized View?](#What-is-the-difference-between-View-and-Materialized-Vie)
+ [What is the main difference between Inmon and Kimball Philosophies of Data Warehousing?](#What-is-the-main-difference-between-Inmon-and-Kimball-Philosophies-of-Data-Warehousin)
+ [What is Junk Dimension and what is the difference between Junk Dimension and Degenerated Dimension?](#What-is-Junk-Dimension-and-what-is-the-difference-between-Junk-Dimension-and-Degenerated-Dimensio)
+ [Why Fact Table is in Normal Form?](#Why-Fact-Table-is-in-Normal-For)
+ [What is difference between Er Modeling and Dimensional Modeling?](#What-is-difference-between-Er-Modeling-and-Dimensional-Modelin)
+ [What is Conformed Fact?](#What-is-Conformed-Fac)
+ [What are the Methodologies of Data Warehousing?](#What-are-the-Methodologies-of-Data-Warehousin)
+ [What is Bus Schema?](#What-is-Bus-Schem)
+ [What is Data Warehousing Hierarchy?](#What-is-Data-Warehousing-Hierarch)
+ [What are Data Validation Strategies for Data Mart Validation after loading process?](#What-are-Data-Validation-Strategies-for-Data-Mart-Validation-after-loading-proces)
+ [What are the Data Types present in Bo and what happens if we implement View in the Designer N Report?](#What-are-the-Data-Types-present-in-Bo-and-what-happens-if-we-implement-View-in-the-Designer-N-Repor)
+ [What is Surrogate Key and where we use it?](#What-is-Surrogate-Key-and-where-we-use-i)
+ [What is a Linked Cube?](#What-is-a-Linked-Cub)
+ [What is meant by Metadata in Context of a Data Warehouse and how it is important?](#What-is-meant-by-Metadata-in-Context-of-a-Data-Warehouse-and-how-it-is-importan)
+ [What are the possible Data Marts in Retail Sales?](#What-are-the-possible-Data-Marts-in-Retail-Sale)
+ [What are the various Etl Tools in the market?](#What-are-the-various-Etl-Tools-in-the-marke)
+ [What is Dimensional Modeling?](#What-is-Dimensional-Modelin)
+ [What is Vldb?](#What-is-Vld)
+ [What is Degenerate Dimension Table?](#What-is-Degenerate-Dimension-Tabl)
+ [What is Er Diagram?](#What-is-Er-Diagra)
+ [What is the difference between Snowflake and Star Schema and what are situations where Snowflake Schema is better than Star Schema?](#What-is-the-difference-between-Snowflake-and-Star-Schema-and-what-are-situations-where-Snowflake-Schema-is-better-than-Star-Schem)
+ [Can a Dimension Table contain numeric values?](#Can-a-Dimension-Table-contain-numeric-value)
+ [What is Hybrid Slowly Changing Dimension?](#What-is-Hybrid-Slowly-Changing-Dimensio)
+ [How many clustered indexes can you create for a table in Dwh and in case Of Truncate and Delete command what happens to table which has unique Id.](#How-many-clustered-indexes-can-you-create-for-a-table-in-Dwh-and-in-case-Of-Truncate-and-Delete-command-what-happens-to-table-which-has-unique-I)
+ [What is Loop in Data Warehousing?](#What-is-Loop-in-Data-Warehousin)
+ [What is an Error Log Table in Informatica occurs and how to maintain it in mapping?](#What-is-an-Error-Log-Table-in-Informatica-occurs-and-how-to-maintain-it-in-mappin)
+ [What is Drilling Across?](#What-is-Drilling-Acros)
+ [Where the Cache Files stored?](#Where-the-Cache-Files-store)
+ [What is Dimension Modeling?](#What-is-Dimension-Modelin)
+ [What is Data Cleaning?](#What-is-Data-Cleanin)
+ [Can you explain the Hierarchies Level Data Warehousing?](#Can-you-explain-the-Hierarchies-Level-Data-Warehousin)
+ [Can you explain about Core Dimension and Balanced Dimension and Dirty Dimension?](#Can-you-explain-about-Core-Dimension-and-Balanced-Dimension-and-Dirty-Dimensio)
+ [What is Core Dimension?](#What-is-Core-Dimensio)
+ [After we create a Scd Table can we use that Particular Dimension as a Dimension Table for Star Schema?](#After-we-create-a-Scd-Table-can-we-use-that-Particular-Dimension-as-a-Dimension-Table-for-Star-Schem)
+ [Suppose you are filtering rows using a Filter Transformation and only rows meet the condition pass to the Target so tell me where rows will go that does not meet condition.](#Suppose-you-are-filtering-rows-using-a-Filter-Transformation-and-only-rows-meet-the-condition-pass-to-the-Target-so-tell-me-where-rows-will-go-that-does-not-meet-conditio)
+ [What is Galaxy Schema?](#What-is-Galaxy-Schem)
+ [Briefly state different between Data Ware House and Data Mart?](#Briefly-state-different-between-Data-Ware-House-and-Data-Mar)
+ [What is MetaData?](#What-is-MetaDat)
+ [What is the Definitions for Datawarehose And Datamart?](#What-is-the-Definitions-for-Datawarehose-And-Datamar)
+ [What is Data Validation Strategies for Data Mart validation after Loading Process](#What-is-Data-Validation-Strategies-for-Data-Mart-validation-after-Loading-Proce)
+ [What is Data Mining?](#What-is-Data-Minin)
+ [What is Ods?](#What-is-Od)
+ [What is Etl?](#What-is-Et)
+ [Is Oltp Database is design optimal for Data Warehouse?](#Is-Oltp-Database-is-design-optimal-for-Data-Warehous)
+ [If Denormalized is improves Data Warehouse Processes and why Fact Table is in Normal Form?](#If-Denormalized-is-improves-Data-Warehouse-Processes-and-why-Fact-Table-is-in-Normal-For)
+ [What are Lookup Tables?](#What-are-Lookup-Table)
+ [What are Aggregate Tables?](#What-are-Aggregate-Table)
+ [What is real time Datawarehousing?](#What-is-real-time-Datawarehousin)
+ [What are Conformed Dimensions?](#What-are-Conformed-Dimension)
+ [How do you load the Time Dimension?](#How-do-you-load-the-Time-Dimensio)
+ [What is a Level of Granularity of a Fact Table?](#What-is-a-Level-of-Granularity-of-a-Fact-Tabl)
+ [What are Non additive facts?](#What-are-Non-additive-fact)
+ [What is Factless Facts Table?](#What-is-Factless-Facts-Tabl)
+ [Explain about Olap?](#Explain-about-Ola)
+ [Explain about the Functionality of Olap?](#Explain-about-the-Functionality-of-Ola)
+ [Explain about Molap?](#Explain-about-Mola)
+ [Explain about Rolap?](#Explain-about-Rola)
+ [Explain about Aggregations?](#Explain-about-Aggregation)
+ [Explain about the View Selection problem?](#Explain-about-the-View-Selection-proble)
+ [Explain about the role of Bitmap Indexes to solve Aggregation Problems?](#Explain-about-the-role-of-Bitmap-Indexes-to-solve-Aggregation-Problem)
+ [Explain about Encoding Technique used in Bitmaps Indexes?](#Explain-about-Encoding-Technique-used-in-Bitmaps-Indexe)
+ [Explain about Binning?](#Explain-about-Binnin)
+ [Explain about Hybrid Olap?](#Explain-about-Hybrid-Ola)
+ [Explain about Shared Features of Olap?](#Explain-about-Shared-Features-of-Ola)
+ [Explain about Analysis?](#Explain-about-Analysi)
+ [Explain about Multidimensional Features present in Olap?](#Explain-about-Multidimensional-Features-present-in-Ola)
+ [Explain about the Database Marketing Application of Olap?](#Explain-about-the-Database-Marketing-Application-of-Ola)
+ [Compare Data Warehouse Database and Oltp Database.](#Compare-Data-Warehouse-Database-and-Oltp-Databas)
+ [What is the difference between Etl Tool and Olap Tool and what are various Etl in the Market?](#What-is-the-difference-between-Etl-Tool-and-Olap-Tool-and-what-are-various-Etl-in-the-Marke)
+ [Steps in building the Data Model.](#Steps-in-building-the-Data-Mode)
+ [Why is Data Modeling important?](#Why-is-Data-Modeling-importan)
+ [What Type of Indexing Mechanism do we need use for a typical Datawarehouse?](#What-Type-of-Indexing-Mechanism-do-we-need-use-for-a-typical-Datawarehous)
+ [What are Semi additive and Factless Facts?](#What-are-Semi-additive-and-Factless-Fact)
+ [Is it correct develop a Data Mart using an Ods?](#Is-it-correct-develop-a-Data-Mart-using-an-Od)
+ [Explain degenerated dimension.](#Explain-degenerated-dimensio)
+ [What are the different methods of loading Dimension Tables?](#What-are-the-different-methods-of-loading-Dimension-Table)
+ [What are Slowly Changing Dimensions?](#What-are-Slowly-Changing-Dimension)
+ [What is meant by Metadata in context of a Datawarehouse?](#What-is-meant-by-Metadata-in-context-of-a-Datawarehous)
+ [What are Modeling Tools available in the Market](#What-are-Modeling-Tools-available-in-the-Mark)
+ [What is the main difference between Schema in Rdbms and Schemas in Datawarehouse?](#What-is-the-main-difference-between-Schema-in-Rdbms-and-Schemas-in-Datawarehous)
+ [What is a general purpose Scheduling Tool?](#What-is-a-general-purpose-Scheduling-Too)
+ [What is the need of Surrogate Key and why Primary Key not used as Surrogate Key?](#What-is-the-need-of-Surrogate-Key-and-why-Primary-Key-not-used-as-Surrogate-Ke)
+ [What is Snow Flake Schema?](#What-is-Snow-Flake-Schem)
+ [What is the difference between Oltp and Olap?](#What-is-the-difference-between-Oltp-and-Ola)
+ [How are the Dimension Tables designed?](#How-are-the-Dimension-Tables-designe)
+ [What are the advantages Data Mining over traditional approaches?](#What-are-the-advantages-Data-Mining-over-traditional-approache)
+ [Which automation tool is used in Data Warehouse testing?](#Which-automation-tool-is-used-in-Data-Warehouse-testin)
+ [Give examples of Degenerated Dimensions.](#Give-examples-of-Degenerated-Dimension)
+ [What is the datatype of the Surrogate Key?](#What-is-the-datatype-of-the-Surrogate-Ke)
+ [What is the difference between scan Component and Rollup Component?](#What-is-the-difference-between-scan-Component-and-Rollup-Componen)
+ [What is M_dump?](#What-is-M_dum)
+ [What is Brodcasting and Replicate?](#What-is-Brodcasting-and-Replicat)
+ [What is Local and Formal Parameter?](#What-is-Local-and-Formal-Paramete)
+ [What is the difference between Dml Expression and Xfr Expression?](#What-is-the-difference-between-Dml-Expression-and-Xfr-Expressio)
+ [Have you used Rollup Component?](#Have-you-used-Rollup-Componen)
+ [What are Primary Keys and Foreign Keys?](#What-are-Primary-Keys-and-Foreign-Key)
+ [What is Outer Join?](#What-is-Outer-Joi)
+ [What are Cartesian Joins?](#What-are-Cartesian-Join)
+ [What is the purpose of having Stored Procedures in a Database?](#What-is-the-purpose-of-having-Stored-Procedures-in-a-Databas)
+ [Why might you create a Stored Procedure with Recompile Option?](#Why-might-you-create-a-Stored-Procedure-with-Recompile-Optio)
+ [What is Cursor?](#What-is-Curso)
+ [Describe process steps you would perform when Defragmenting a Data Table and this table contains mission critical Data?](#Describe-process-steps-you-would-perform-when-Defragmenting-a-Data-Table-and-this-table-contains-mission-critical-Dat)
+ [Explain the difference between Truncate and Delete Commands?](#Explain-the-difference-between-Truncate-and-Delete-Command)
+ [How would you find out whether Sql Query is using Indices you Expect?](#How-would-you-find-out-whether-Sql-Query-is-using-Indices-you-Expec)
+ [What are the Security Level used in Bo?](#What-are-the-Security-Level-used-in-B)
+ [What are the Functional and Architectural differences between Business Objects and Web Intelligence Reports?](#What-are-the-Functional-and-Architectural-differences-between-Business-Objects-and-Web-Intelligence-Report)
+ [What is batch processing in Business Objects?](#What-is-batch-processing-in-Business-Object)
+ [What is Data Cardinality?](#What-is-Data-Cardinalit)
+ [What is Chained Data Replication?](#What-is-Chained-Data-Replicatio)
+ [Explain in brief various fundamental stages of Data Warehousing.](#Explain-in-brief-various-fundamental-stages-of-Data-Warehousin)
+ [What is the difference between Enterprise Data Warehouse and Data Warehouse?](#What-is-the-difference-between-Enterprise-Data-Warehouse-and-Data-Warehous)
+ [Give me any example of Semi and Non Additive Measures?](#Give-me-any-example-of-Semi-and-Non-Additive-Measure)
+ [What are the options in the Target Session of Update Strategy Transformations?](#What-are-the-options-in-the-Target-Session-of-Update-Strategy-Transformation)
+ [What are the Various Types of Transformation?](#What-are-the-Various-Types-of-Transformatio)
+ [What is the difference between Active Transformation and Passive Transformation?](#What-is-the-difference-between-Active-Transformation-and-Passive-Transformatio)
+ [What is the difference between Static Cache and Dynamic Cache?](#What-is-the-difference-between-Static-Cache-and-Dynamic-Cach)
+ [How do we join Two tables without Joiner or Sql Override?](#How-do-we-join-Two-tables-without-Joiner-or-Sql-Overrid)
+ [Differences between Normalizer and Normalizer Transformation.](#Differences-between-Normalizer-and-Normalizer-Transformatio)
+ [What is Business Intelligence?](#What-is-Business-Intelligenc)
+ [What is a Universe in Business Intelligence?](#What-is-a-Universe-in-Business-Intelligenc)
+ [What is Olap in Business Intelligence?](#What-is-Olap-in-Business-Intelligenc)
+ [What are various Modules in Business Objects Product?](#What-are-various-Modules-in-Business-Objects-Produc)
+ [What is Olap Molap Rolap Dolap Holap?](#What-is-Olap-Molap-Rolap-Dolap-Hola)
+ [Why an Infocube has maximum of 16 dimensions?](#Why-an-Infocube-has-maximum-of-16-dimension)
+ [Name some standard Business Intelligence Tools in the Market?](#Name-some-standard-Business-Intelligence-Tools-in-the-Marke)
+ [What are Dashboards?](#What-are-Dashboard)
+ [What is Hierarchy Relationship in a Dimension.](#What-is-Hierarchy-Relationship-in-a-Dimensio)
+ [What are Adhoc reports and Static Reports?](#What-are-Adhoc-reports-and-Static-Report)
+ [What is the Importance of Surrogate Key in Data Warehousing?](#What-is-the-Importance-of-Surrogate-Key-in-Data-Warehousin)
+ [What is a Query?](#What-is-a-Quer)
+ [What are the Features of a Physical Data Model?](#What-are-the-Features-of-a-Physical-Data-Mode)
+ [What are the steps to design a Physical Model?](#What-are-the-steps-to-design-a-Physical-Mode)
+ [What are the Features of Conceptual Data Model?](#What-are-the-Features-of-Conceptual-Data-Mode)
+ [What are the difference between Logical Data Model and Conceptual Data Model?](#What-are-the-difference-between-Logical-Data-Model-and-Conceptual-Data-Mode)
+ [What are the steps to design Logical Data Model?](#What-are-the-steps-to-design-Logical-Data-Mode)
+ [What is Etl?](#What-is-Et)
+ [What is a Three Tier Data Warehouse?](#What-is-a-Three-Tier-Data-Warehous)
+ [What is Etl Process and how many steps Etl contains?](#What-is-Etl-Process-and-how-many-steps-Etl-contain)
+ [What is Full Load and Incremental or Refresh Load?](#What-is-Full-Load-and-Incremental-or-Refresh-Loa)
+ [What is a Staging Area?](#What-is-a-Staging-Are)
+ [Compare Etl and Manual Development.](#Compare-Etl-and-Manual-Developmen)
+ [What is Rdbms?](#What-is-Rdbm)
+ [What is Normalization?](#What-is-Normalizatio)
+ [What are different Normalization Forms?](#What-are-different-Normalization-Form)
+ [What is Stored Procedure?](#What-is-Stored-Procedur)
+ [What is Trigger?](#What-is-Trigge)
+ [What is View?](#What-is-Vie)
+ [Advantages of Dbms?](#Advantages-of-Dbm)
+ [Disadvantage in File Processing System?](#Disadvantage-in-File-Processing-Syste)
+ [Describe Three Levels of Data Abstraction?](#Describe-Three-Levels-of-Data-Abstractio)
+ [Define integrity Rules?](#Define-integrity-Rule)
+ [What is Extension and Intention?](#What-is-Extension-and-Intentio)
+ [What is Data Independence?](#What-is-Data-Independenc)
+ [What is a View and how it is related to Data Independence?](#What-is-a-View-and-how-it-is-related-to-Data-Independenc)
+ [What is Data Model?](#What-is-Data-Mode)
+ [What is Object Oriented Model?](#What-is-Object-Oriented-Mode)
+ [What is an Entity?](#What-is-an-Entit)
+ [What is an Entity Type?](#What-is-an-Entity-Typ)
+ [What is an Entity Set?](#What-is-an-Entity-Se)
+ [What is an Attribute?](#What-is-an-Attribut)
+ [What is Relation Schema and Relation?](#What-is-Relation-Schema-and-Relatio)
+ [What is Degree of Relation?](#What-is-Degree-of-Relatio)
+ [What is Relationship?](#What-is-Relationshi)
+ [What is Relationship Set?](#What-is-Relationship-Se)
+ [What is Relationship Type?](#What-is-Relationship-Typ)
+ [What Is DDL?](#What-Is-DD)
+ [What Is Vdl?](#What-Is-Vd)
+ [What is Sdl?](#What-is-Sd)
+ [What Is Data Storage Definition Language?](#What-Is-Data-Storage-Definition-Languag)
+ [What Is Dml?](#What-Is-Dm)
+ [What is Query Evaluation Engine?](#What-is-Query-Evaluation-Engin)
+ [What is Ddl Interpreter?](#What-is-Ddl-Interprete)
+ [What is Record at a time?](#What-is-Record-at-a-tim)
+ [What is Set at a time or Set oriented?](#What-is-Set-at-a-time-or-Set-oriente)
+ [What is Relational Algebra?](#What-is-Relational-Algebr)
+ [What is Relational Calculus?](#What-is-Relational-Calculu)
+ [How does Tuple oriented Relational calculus differ from Domain oriented Relational Calculus?](#How-does-Tuple-oriented-Relational-calculus-differ-from-Domain-oriented-Relational-Calculu)
+ [What is Functional Dependency?](#What-is-Functional-Dependenc)
+ [What is Multivalued Dependency?](#What-is-Multivalued-Dependenc)
+ [What is Lossless Join Property?](#What-is-Lossless-Join-Propert)
+ [What Is 1 Nf?](#What-Is-1-N)
+ [What is Fully Functional Dependency?](#What-is-Fully-Functional-Dependenc)
+ [What is 2nf?](#What-is-2n)
+ [What is 3nf?](#What-is-3n)
+ [What is 4nf?](#What-is-4n)
+ [What is 5nf?](#What-is-5n)
+ [What is Domain key NF?](#What-is-Domain-key-N)
+ [What are Partial Alternate Artificial Compound and Natural Key?](#What-are-Partial-Alternate-Artificial-Compound-and-Natural-Ke)
+ [What is Indexing and what are the different kinds of Indexing?](#What-is-Indexing-and-what-are-the-different-kinds-of-Indexin)
+ [What is meant by Query Optimization?](#What-is-meant-by-Query-Optimizatio)
+ [What is Join Dependency and Inclusion Dependency?](#What-is-Join-Dependency-and-Inclusion-Dependenc)
+ [What is Durability in Dbms?](#What-is-Durability-in-Dbm)
+ [What do you mean by Atomicity and Aggregation?](#What-do-you-mean-by-Atomicity-and-Aggregatio)
+ [What is Phantom Deadlock?](#What-is-Phantom-Deadloc)
+ [What is Checkpoint and when does it cccur?](#What-is-Checkpoint-and-when-does-it-cccu)
+ [What are different Phases of Transaction?](#What-are-different-Phases-of-Transactio)
+ [What do you mean by Flat File Database?](#What-do-you-mean-by-Flat-File-Databas)
+ [What is transparent Dbms?](#What-is-transparent-Dbm)
+ [What do you mean by Correlated Subquery?](#What-do-you-mean-by-Correlated-Subquer)
+ [What are the Primitive Operations common to all record management systems?](#What-are-the-Primitive-Operations-common-to-all-record-management-system)
+ [What are Unary Operations in Relational Algebra?](#What-are-Unary-Operations-in-Relational-Algebr)
+ [Are resulting Relations of Product and Join Operation the same?](#Are-resulting-Relations-of-Product-and-Join-Operation-the-sam)
+ [What is Rdbms Kernel?](#What-is-Rdbms-Kerne)
+ [Name the Sub systems of Rdbms?](#Name-the-Sub-systems-of-Rdbm)
+ [What is Rowid?](#What-is-Rowi)
+ [What is Storage Manager?](#What-is-Storage-Manage)
+ [What is Buffer Manager?](#What-is-Buffer-Manage)
+ [What is Transaction Manager?](#What-is-Transaction-Manage)
+ [What is File Manager?](#What-is-File-Manage)
+ [What is Authorization and Integrity Manager?](#What-is-Authorization-and-Integrity-Manage)
+ [What are Stand alone procedures?](#What-are-Stand-alone-procedure)
+ [What are the different methods of loading dimension tables?](#What-are-the-different-methods-of-loading-dimension-table)
+ [Describe the foreign key columns in fact tables and dimension tables?](#Describe-the-foreign-key-columns-in-fact-tables-and-dimension-table)

[Table of Contents](#Data-Warehousing-Architecture)

## What is the Main Difference between View and Materialized View?
A view and a materialized view are database objects that provide a logical representation of data in a database. However, there is a significant difference between the two.

A view is a virtual table based on a SELECT statement. It does not store any data on disk and instead derives its data from one or more tables. When a query is executed against a view, the database engine retrieves the data from the underlying tables and presents it to the user as if it were a table. Views are useful for presenting complex queries in a simplified manner, enforcing security policies, and providing a consistent view of data to multiple users.

On the other hand, a materialized view is a physical copy of a view. It stores the result set of a query in a table-like structure on disk, making it faster to access the data. A materialized view is updated periodically (either automatically or manually) to ensure that the data it contains is up-to-date. Materialized views are often used to speed up queries on large tables or to precompute complex aggregations.

In summary, the main difference between a view and a materialized view is that a view is a virtual table that does not store data on disk, while a materialized view is a physical copy of a view that stores data on disk. Materialized views are more expensive to create and maintain, but they offer faster query performance and can be useful for speeding up complex queries.

[Table of Contents](#Data-Warehousing-Architecture)

## What is Junk Dimension?
In data warehousing, a junk dimension is a dimension table that is created by combining several low-cardinality attributes (i.e., attributes with a small number of distinct values) from multiple dimensions into a single table. The purpose of a junk dimension is to simplify the design of a data warehouse by reducing the number of dimension tables and improving query performance.

A junk dimension table typically contains a single column that concatenates the various low-cardinality attributes, along with a surrogate key that serves as the primary key of the table. For example, a junk dimension table might contain attributes such as product color, size, and shape, which are all low-cardinality attributes that could be combined into a single table.

By combining these attributes into a single table, the number of dimension tables in the data warehouse is reduced, which can simplify the schema and make it easier to maintain. In addition, queries that involve these attributes can be faster, since they can be answered by referencing a single junk dimension table instead of multiple dimension tables.

Overall, a junk dimension can be a useful technique for simplifying the design of a data warehouse and improving query performance when dealing with low-cardinality attributes.

Sure, here's an example of a junk dimension:
Suppose you have a data warehouse for a retail store that sells clothing. You have a fact table that records sales transactions, and several dimension tables such as Product, Store, Time, and Customer. The Product dimension table has several attributes such as Brand, Category, Subcategory, and Gender.
However, you also have several low-cardinality attributes that are not large enough to warrant their own dimension table, such as Product Color, Size, and Style. Instead of creating separate dimension tables for each of these attributes, you can combine them into a single junk dimension table.
The junk dimension table might look like this:

Refer chat GPT for the examples.
No, a junk dimension table does not store a Cartesian product of all possible combinations of the low-cardinality attributes. Instead, it stores only the distinct combinations of values that actually appear in the fact table.


[Table of Contents](#Data-Warehousing-Architecture)

## What is Data Warehouse architecture?
Data Warehouse architecture is the design and structure of a data warehouse system that supports the process of extracting, transforming, and loading data from various sources into a central repository for reporting and analysis purposes.

There are several common architectures for data warehousing, but a typical data warehouse architecture consists of the following components:

Source systems: These are the systems that provide the data that is loaded into the data warehouse. Source systems may include operational databases, external data sources, or other systems.

ETL (Extract, Transform, Load) processes: These are the processes that extract data from source systems, transform it into a format that is suitable for analysis, and load it into the data warehouse. ETL processes may include data cleansing, data integration, data aggregation, and data validation.

Data storage: This is where the data is stored in the data warehouse. The data storage component typically includes a combination of a relational database management system (RDBMS) and data storage structures such as star schema or snowflake schema.

Metadata: This is the data that describes the data in the data warehouse, including data definitions, data lineage, and data relationships.

OLAP (Online Analytical Processing) engines: These are the tools used to access and analyze the data in the data warehouse. OLAP engines provide multidimensional views of the data, allowing users to analyze data from different perspectives.

Reporting and analysis tools: These are the tools used by end users to query the data warehouse, generate reports, and perform analysis on the data. These tools may include dashboarding and visualization software, business intelligence tools, and statistical analysis software.

Overall, a well-designed data warehouse architecture should provide a scalable, flexible, and reliable platform for storing and analyzing data, enabling organizations to make better-informed business decisions based on timely and accurate information.

[Table of Contents](#Data-Warehousing-Architecture)

## What is an integrity constraints and what are different types of integrity constraints?
Integrity constraints are rules that are defined for a database schema to maintain the accuracy and consistency of the data stored in it. These constraints enforce the validity and correctness of the data in the database and prevent the entry of inconsistent or incorrect data.

There are several types of integrity constraints, including:

Domain constraints: These are constraints that define the allowable values for an attribute in a database table. For example, a domain constraint may limit the values that can be entered in a "gender" field to "Male" or "Female".

Entity integrity constraints: These are constraints that ensure that each row in a database table is unique and can be identified by a unique primary key value. For example, a table containing customer information may have a primary key constraint on the "customer ID" field, ensuring that each customer has a unique ID.

Referential integrity constraints: These are constraints that ensure that relationships between tables are maintained correctly. For example, if a table has a foreign key that references a primary key in another table, referential integrity constraints ensure that the foreign key value always references a valid primary key value in the other table.

Check constraints: These are constraints that define conditions that must be satisfied for a record to be entered or updated in a database table. For example, a check constraint may ensure that a date value entered in a table is within a certain range.

Business rules: These are constraints that define additional rules or conditions that must be satisfied to maintain the integrity of the data in a database. For example, a business rule may require that an employee's salary cannot be less than the minimum wage.

By enforcing these constraints, a database system can ensure that the data stored in it is accurate, consistent, and valid, thereby enhancing the overall quality of the database and its ability to support business operations.

[Table of Contents](#Data-Warehousing-Architecture)

## Why is that Data Architect actually monitor and enforce compliance data standards?
The primary idea of keeping the standards high on compliance for data standards is because it will help to reduce the data redundancy and helps the team to have a quality data. As this information is actually carried out or used throughout the organization.

[Table of Contents](#Data-Warehousing-Architecture)

## Explain the different data models that are available in detail?
here's an explanation of the conceptual, logical, and physical data models, along with an example:

Conceptual Data Model:
The conceptual data model describes the high-level business concepts and entities in a database system. It focuses on the big picture of the data, without getting into too much detail about how it will be implemented or organized. The conceptual model is typically created during the requirements gathering phase of the database design process.
Example: A conceptual data model for an online retail store might include entities such as "customer," "order," "product," and "shipping address." It would show the relationships between these entities, such as the fact that each order is associated with a customer, and each customer can have multiple orders.

Logical Data Model:
The logical data model is a more detailed representation of the data than the conceptual model. It describes the entities, attributes, relationships, and constraints of the data in a way that is independent of any specific database management system or implementation. The logical model serves as a blueprint for the actual database schema.
Example: A logical data model for the online retail store might include detailed definitions of the "customer" entity, including attributes such as "customer ID," "name," "email address," and "phone number." It would also include the relationships between entities, such as the fact that each order has a "customer ID" foreign key that references the "customer" entity.

Physical Data Model:
The physical data model is the actual implementation of the database schema in a specific database management system. It includes details such as table names, column types, indexes, and constraints. The physical model is optimized for the specific database management system being used and takes into account performance and scalability considerations.
Example: The physical data model for the online retail store would include the actual tables and columns in the database, such as a "customer" table with columns for "customer ID," "name," "email address," and "phone number." It would also include indexes and constraints, such as a unique index on the "customer ID" column to enforce uniqueness.

[Table of Contents](#Data-Warehousing-Architecture)

## Differentiate between dimension and attribute?
In short, dimensions are nothing but which represents qualitative data. For example data like a plan, product, class are all considered as dimensions.
The attribute is nothing but a subset of a dimension. Within a dimension table, we will have attributes. The attributes can be textual or descriptive. For example, product name and product category are nothing but an attribute of product dimensions.

[Table of Contents](#Data-Warehousing-Architecture)

## Differentiate between Oltp and Olap?
OLTP (Online Transaction Processing) and OLAP (Online Analytical Processing) are two distinct data processing systems that serve different purposes. Here are the key differences between the two:

Purpose:
OLTP systems are designed for transactional processing, which involves managing and processing a large number of individual transactions, such as orders, payments, and inventory updates. The focus is on capturing and updating data in real-time to support day-to-day operations. In contrast, OLAP systems are designed for analytical processing, which involves aggregating and analyzing large volumes of data to support strategic decision-making. The focus is on providing business intelligence and insights into trends and patterns in the data.

Data:
OLTP systems deal with operational data that is constantly being updated in real-time, such as sales transactions, customer orders, and inventory updates. The data is usually structured and optimized for fast processing and retrieval. OLAP systems deal with historical data that is typically stored in a data warehouse or data mart. The data is usually structured and optimized for complex queries and analytics.

Query Complexity:
OLTP systems handle simple, low-complexity queries that are designed to retrieve individual records or update small sets of data. The focus is on fast response times and transactional consistency. In contrast, OLAP systems handle complex queries that involve aggregating and analyzing large volumes of data. The focus is on providing accurate and timely answers to complex business questions.

User Base:
OLTP systems are typically used by operational staff, such as salespeople, customer service representatives, and inventory managers. The focus is on data entry and processing to support day-to-day operations. In contrast, OLAP systems are typically used by analysts and decision-makers who need access to aggregated and summarized data to support strategic decision-making.

Data Model:
OLTP systems use a normalized data model that is optimized for transactional processing and data consistency. The focus is on avoiding data redundancy and ensuring data integrity. In contrast, OLAP systems use a denormalized data model that is optimized for analytical processing and query performance. The focus is on aggregating and summarizing data to support complex analytics.

OLTP systems are typically better for writing operations, while OLAP systems are better for reading and analyzing large volumes of data.

Overall, OLTP systems and OLAP systems are designed for different purposes and serve different user bases. While OLTP systems are optimized for fast transaction processing and data consistency, OLAP systems are optimized for complex queries and analytics that support strategic decision-making.

[Table of Contents](#Data-Warehousing-Architecture)

## What is a Real time Data Warehouse and how is it different from near to Real time Data Warehouse?
As the term suggests, a real-time data warehouse is a system, which reflects all changes to its sources in real time. As simple as it sounds, this is still an area of active research in the field. In traditional DWH, the operational system(s) are kept separate from the DWH for a good reason.
The Operational systems are designed to accept inputs or changes to data regularly, hence have a good chance of being regularly queried. On the other hand, a DWH is supposed to do just the opposite - it is used to query data for reports only. No changes to data, through user actions is expected (or designed). The only inputs could come from the ETL feed at stipulated times.
The ETL would source its data from the Operational systems just explained above.
To create a real-time DWH we would have to merge both systems (several ways are being explored), a concept that is against the reason of creating a DWH. Bigger challenges occur in terms of updating aggregated data in facts at real time, still maintaining the surrogate keys.
Besides, we would need lightening fast hardware to try this.Near Real time DWH is a trade-off between the conventional design and the dream of all clients today. The frequency of ETL updates in higher in this case for e.g. once in 2 hours. We can also analyze and use selective refreshes at shorter time intervals, while complete refreshes may still be kept further apart. Selective refreshes would look at only those tables that get updated regularly.

[Table of Contents](#Data-Warehousing-Architecture)

## What is Type 2 Version Dimension?
Slowly Changing Dimensions (SCD) refer to the data attributes in a data warehouse that change over time, but at a relatively slow rate. These dimensions require special treatment when designing and implementing data warehouse solutions because the changes must be tracked and managed effectively to ensure data consistency and accuracy.

SCD can be categorized into three types:

Type 1 SCD: Overwrite: In this approach, changes to the dimension are simply overwritten with new data, with no historical tracking of previous values. This approach is best suited for dimensions that do not require historical tracking of changes, such as the names and addresses of customers.

Type 2 SCD: Add New Record: In this approach, a new record is added to the dimension table to represent the change, with the old record being marked as inactive or expired. This approach is best suited for dimensions that require historical tracking of changes, such as product prices and promotions.

Type 3 SCD: Add New Column: In this approach, a new column is added to the dimension table to capture the change, with the previous value being overwritten. This approach is best suited for dimensions that require limited historical tracking of changes, such as the status of a customer.

The implementation of SCD in a data warehouse involves designing the dimension tables to support historical tracking of changes. This can be achieved by adding additional columns to the dimension tables to capture information such as start and end dates for each record, version numbers, or flags to indicate active or inactive records.

When a change occurs in a dimension, the appropriate SCD strategy is applied to capture and manage the change. For example, in Type 2 SCD, a new record is inserted into the dimension table with a new version number and start date, and the previous record is marked as inactive or expired by updating the end date.

SCD is an important concept in data warehousing because it ensures data consistency and accuracy over time. By tracking changes to slowly changing dimensions, data warehouse users can analyze historical trends and make informed business decisions based on accurate and reliable data.

Here is an example of how to design SCD Type 2 for a customer dimension table:

Identify the columns that need to be tracked: In the customer dimension table, we need to track the name, address, phone number, and email address columns.

Add effective date and expiry date columns: Add two columns, Effective_Date and Expiry_Date, to the customer dimension table to track the effective and expiry dates of each record.

Add a surrogate key: Add a surrogate key column, Customer_Key, to the customer dimension table to uniquely identify each record.

Add a current indicator: Add a current indicator column, Current_Indicator, to the customer dimension table to identify the current active record.

Create a new record for changes: When a customer changes their address, create a new record in the customer dimension table with a new Customer_Key, updated Effective_Date, and expiry date of the previous record.

Update the previous record: Update the Expiry_Date of the previous record to the day before the Effective_Date of the new record.

Set the current indicator: Set the Current_Indicator to 1 for the new record and 0 for the previous record.

By using both the Effective_Date and Expiry_Date columns and the Current_Indicator column, we can track the historical changes to the dimension data while still identifying the current active record. This approach allows us to maintain historical data consistency and accuracy while still providing quick access to the current information.

For example, suppose we are analyzing sales data and need to determine the customer's address at the time of the sale. By using the Effective_Date and Expiry_Date columns, we can determine which customer address was valid at the time of the sale. And by using the Current_Indicator column, we can quickly identify the current customer address if needed.

Therefore, having both the Effective_Date and Expiry_Date columns and the Current_Indicator column is essential for tracking historical changes while still identifying the current state of a dimension record.

[Table of Contents](#Data-Warehousing-Architecture)

## What are Data Modeling and Data Mining?
Data modeling is the process of designing a data base model. In this data model data will be stored in two types of table fact table and dimension table.
Fact table contains the transaction data and dimension table contains the master data. Data mining is process of finding the hidden trends is called the data mining.

[Table of Contents](#Data-Warehousing-Architecture)

## Where the Data Cube Technology is used?
A multi-dimensional structure called the data cube. A data abstraction allows one to view aggregated data from a number of perspectives. Conceptually, the cube consists of a core or base cuboids, surrounded by a collection of sub-cubes/cuboids that represent the aggregation of the base cuboids along one or more dimensions. We refer to the dimension to be aggregated as the measure attribute, while the remaining dimensions are known as the feature attributes.

[Table of Contents](#Data-Warehousing-Architecture)

## How can you implement many relations in Star Schema Model?
n a Star Schema Model, it is possible to implement many-to-many relationships between dimension tables by using a bridge table or factless fact table. Here is an example of how to implement many-to-many relationships in a Star Schema Model:

Let's consider a scenario where we have a sales transaction fact table that has a many-to-many relationship with both a customer dimension table and a product dimension table. A customer can purchase multiple products, and a product can be purchased by multiple customers.

To implement this many-to-many relationship, we can create a bridge table that sits between the sales transaction fact table and the customer and product dimension tables. This bridge table contains the primary keys from both the customer and product dimension tables, along with any additional attributes that we want to track for this relationship.

For example, we could create a Sales_Customer_Product bridge table with the following columns:

Sales_Key (foreign key to the sales transaction fact table)
Customer_Key (foreign key to the customer dimension table)
Product_Key (foreign key to the product dimension table)
Purchase_Date
Quantity
Sale_Amount
Each record in the bridge table represents a customer's purchase of a specific product in a sales transaction. By joining the sales transaction fact table to the bridge table and then to the customer and product dimension tables, we can analyze sales data at the customer and product level, even though there is a many-to-many relationship between them.

In summary, to implement many-to-many relationships in a Star Schema Model, we can create a bridge table or a factless fact table that sits between the fact table and the dimension tables. This table allows us to track additional attributes related to the relationship and enables us to analyze data at the dimension level despite the many-to-many relationship.

[Table of Contents](#Data-Warehousing-Architecture)

## What is Critical Column?
Let us take one ex: Suppose 'XYZ' is customer in Bangalore, he was residing in the city from the last 5 years, in the period of 5 years he has made purchases worth of 3 lacs. Now, he moved to 'HYD'. When you update the 'XYZ' city to 'HYD' in your Warehouse, all the purchases by him will show in city 'HYD' only. This makes warehouse inconsistent. Here CITY is the Critical Column. Solution is use Surrogate Key.

[Table of Contents](#Data-Warehousing-Architecture)

## What is the main difference between Star and Snowflake Star Schema and which one is better and why?
The main difference between a Star Schema and a Snowflake Schema is how they handle dimension tables. In a Star Schema, dimension tables are denormalized, meaning they are stored in a single table with all the attributes, while in a Snowflake Schema, dimension tables are normalized, meaning they are split into multiple related tables, creating a hierarchical structure.

The advantage of a Star Schema is that it is simple and easy to understand. It has fewer tables, making queries faster and easier to write. The data is stored in a single table, making it easy to maintain and update. Star Schema is generally recommended for small to medium-sized data warehouses and is ideal for ad-hoc queries and reporting.

The advantage of a Snowflake Schema is that it reduces data redundancy and improves data integrity by normalizing dimension tables. It allows for more flexible and precise queries, as we can query only the required attributes. Snowflake Schema is recommended for large data warehouses with complex relationships between dimension tables, where data updates are less frequent. Snowflake Schema is ideal for complex analytical queries, especially when dealing with large amounts of data.

Therefore, the choice between Star Schema and Snowflake Schema depends on the specific requirements of the data warehouse. If the data warehouse is small to medium-sized and has a relatively simple structure, a Star Schema would be a good choice. If the data warehouse is large, with complex relationships between dimension tables, and requires complex analytical queries, a Snowflake Schema would be a better choice.

[Table of Contents](#Data-Warehousing-Architecture)

## What is the difference between Dependent Data Warehouse and Independent Data Warehouse?
Dependent departments are those, which depend on a data ware to for their data.Independent department are those, which get their data directly from the operational data sources in the organization.

[Table of Contents](#Data-Warehousing-Architecture)

## Which technology should be used for interactive Data Querying across multiple dimensions for a decision making for a Dw?
MOLAP

[Table of Contents](#Data-Warehousing-Architecture)

## What is Virtual Data Warehousing?
A virtual or point-to-point data warehousing strategy means that end-users are allowed to get at operational databases directly using whatever tools are enabled to the "data access network".

[Table of Contents](#Data-Warehousing-Architecture)

## What is the difference between Metadata and Data Dictionary?
Metadata is data that describes other data. It provides information about the structure, content, and context of the data. Metadata can be used to help manage data, understand its meaning, and ensure its quality. Examples of metadata include data types, field lengths, table names, and relationships between tables.

A Data Dictionary, on the other hand, is a specific type of metadata that provides a comprehensive description of the data elements used in a database or information system. It contains information about the data elements, including their names, definitions, attributes, data types, and relationships to other data elements. The Data Dictionary also includes information about the database structure, such as tables, views, indexes, and constraints.

In other words, Metadata is a broader term that includes any information about the data, while a Data Dictionary is a specific type of metadata that provides a structured and standardized description of the data elements.

To summarize, Metadata is any data that describes other data, while a Data Dictionary is a specific type of metadata that provides a detailed description of the data elements in a database or information system.

[Table of Contents](#Data-Warehousing-Architecture)

## What is the difference between Mapping Parameter and Mapping Variable in Data Warehousing?
In Data Warehousing, Mapping Parameter and Mapping Variable are both used in ETL (Extract, Transform, Load) processes to facilitate the data flow, but they serve different purposes.

Mapping Parameter is a user-defined value that is used to pass a value from one mapping to another mapping, or from a workflow to a mapping. It is a constant value that does not change during the execution of the mapping or workflow. Mapping parameters are defined at the mapping level, and they can be used to parameterize a mapping, making it more flexible and reusable.

Mapping Variable, on the other hand, is a user-defined value that can change during the execution of a mapping. Mapping variables are defined at the session level, and they can be used to store intermediate values during the data transformation process. Mapping variables can be set to a value at the start of a session, and their value can be updated by the mapping as it runs. Mapping variables are commonly used for complex data transformation logic, or for calculations that require multiple steps.

To summarize, Mapping Parameter is a constant value that does not change during the execution of a mapping or workflow, while Mapping Variable is a value that can change during the execution of a mapping and is commonly used for complex data transformation logic.

[Table of Contents](#Data-Warehousing-Architecture)

## Explain the advantages Of Raid 1 and 1/0 And 5 and what type of Raid setup would you put your Tx Logs.
The basic advantage of RAID is to speed up the data reading from permanent storage device (hard disk).

[Table of Contents](#Data-Warehousing-Architecture)

## What are the characteristics of data files?
A data file can be associated with only one database. Once created a data file can't change size. One or more data files form a logical unit of database storage called a table space.

[Table of Contents](#Data-Warehousing-Architecture)

## What is Rollback Segment?
A Database contains one or more Rollback Segments to temporarily store "undo" information.

[Table of Contents](#Data-Warehousing-Architecture)

## What is a Table Space?
Different types of database objects can be stored in different tablespaces, depending on their size, access patterns, and performance requirements. For example, large tables or indexes might be stored in their own dedicated tablespaces to improve performance, while smaller tables or indexes might be grouped together in a shared tablespace.

In summary, a tablespace is a logical storage unit in a database that is used to group related database objects together for more efficient storage and management of storage resources.
Suppose you have a database for a retail store that sells products online. The database contains several tables, including a product table, a customer table, and an order table. In this case, you might create several tablespaces to store these tables:

Product Tablespace - This tablespace would contain the product table, which stores information about all the products sold by the store, including their names, descriptions, prices, and inventory levels.

Customer Tablespace - This tablespace would contain the customer table, which stores information about all the customers who have purchased products from the store, including their names, addresses, and contact information.

Order Tablespace - This tablespace would contain the order table, which stores information about all the orders placed by customers, including the products ordered, the order date, and the shipping information.

By grouping related tables together in separate tablespaces, you can better manage the physical storage of data in your database. For example, you can allocate more storage space to the Product Tablespace if you know that it will contain a large amount of data, or you can optimize performance by placing the most frequently accessed tables in a separate tablespace.

[Table of Contents](#Data-Warehousing-Architecture)

## What is Database Link?
A database link is a named object that describes a "path" from one database to another.

[Table of Contents](#Data-Warehousing-Architecture)

## What is a Hash Cluster?
A row is stored in a hash cluster based on the result of applying a hash function to the row's cluster key value. All rows with the same hash key value are stores together on disk.

[Table of Contents](#Data-Warehousing-Architecture)

## Describe referential Integrity?
Referential integrity is a fundamental concept in database management that ensures that relationships between tables are consistent and valid. It is the property of a database that ensures that the relationships between tables are enforced and maintained.

Referential integrity is enforced through the use of foreign keys, which are used to establish a link between two tables. A foreign key is a field or set of fields in one table that refers to the primary key of another table. The primary key is a unique identifier for each record in the table, while the foreign key is used to associate a record in one table with a record in another table.

When referential integrity is enforced, the database management system ensures that any changes made to the primary key value in the referenced table are automatically reflected in the foreign key values in the referring table. This ensures that the relationships between tables are always valid and consistent.

For example, consider a database with two tables, a customer table and an order table. The customer table has a primary key called "CustomerID", while the order table has a foreign key called "CustomerID" that references the "CustomerID" field in the customer table. This means that each order must be associated with a valid customer ID in the customer table.

If a user tries to insert an order with an invalid customer ID, the database management system will reject the insertion and generate an error message. Similarly, if a user tries to delete a customer record that has associated orders, the system will prevent the deletion and generate an error message.

In summary, referential integrity is a set of rules that ensure that the relationships between tables in a database are consistent and valid. It is enforced through the use of foreign keys and helps maintain the accuracy and reliability of the data in the database.

[Table of Contents](#Data-Warehousing-Architecture)

## What is Schema vs Database?
A database is a collection of related data that is organized and stored in a specific way to allow for efficient data retrieval, manipulation, and management. It can be thought of as a container that holds all the data related to a specific application or set of applications.

A schema, on the other hand, is a logical container for database objects such as tables, views, procedures, functions, etc. It defines the structure of the database, including the relationships between different objects, and provides a blueprint for creating, modifying, and querying the database.

To put it simply, a database is a physical container for data, while a schema is a logical container for objects within that database.

For example, consider a university database that contains data about students, courses, grades, and faculty. The database itself would be the container that holds all of this data, while the schema would be the logical structure that defines the relationships between the different objects within the database. The schema might include tables for students, courses, and faculty, as well as views and stored procedures for querying and updating the data in these tables.

In summary, a database is a physical entity that stores data, while a schema is a logical entity that defines the structure and relationships of the objects within that database.

[Table of Contents](#Data-Warehousing-Architecture)

## What is Table?
A table is the basic unit of data storage in an ORACLE database. The tables of a database hold all of the user accessible data. Table data is stored in rows and columns.

[Table of Contents](#Data-Warehousing-Architecture)

## What is a View?
A view is a virtual table. Every view has a Query attached to it. (The Query is a SELECT statement that identifies the columns and rows of the table(s) the view uses.)

[Table of Contents](#Data-Warehousing-Architecture)

## What is an Extent?
An Extent is a specific number of contiguous data blocks, obtained in a single allocation, and used to store a specific type of information.

[Table of Contents](#Data-Warehousing-Architecture)

## What is an Index?
n database management, an index is a data structure that is used to improve the speed of data retrieval operations on a table. An index is created on one or more columns of a table and contains a sorted list of values from those columns, along with a pointer to the corresponding row in the table.

When a query is executed that involves the indexed column(s), the database engine uses the index to quickly locate the rows that match the query criteria, rather than scanning the entire table. This can significantly improve the performance of read operations on large tables.

Indexes can be created on single or multiple columns of a table, depending on the query patterns and performance requirements. There are different types of indexes available in most database systems, including clustered, non-clustered, unique, and composite indexes.

While indexes can improve the performance of read operations, they can also have some drawbacks, such as increased storage space and slower write operations. Therefore, it is important to carefully plan and design indexes based on the specific requirements and usage patterns of the database.

In summary, an index is a data structure that improves the performance of data retrieval operations on a table by providing a sorted list of values and a pointer to the corresponding rows. They can significantly improve the read performance of large tables, but need to be designed and used carefully to avoid negative impacts on write performance and storage space.

Indexing can have a negative impact on write operations for a few reasons:

Overhead: When you create an index on a table, the database system needs to maintain the index data structure as you add, modify, or delete records in the table. This can add overhead to write operations, as the system needs to update the index as well as the table data.

Indexing can slow down insert operations: When you insert a new record into a table with an index, the database system needs to update the index to include the new record. This can be a time-consuming operation, especially if the index is large, and can slow down insert operations.

Indexing can increase disk usage: Indexes are stored separately from the table data, so adding indexes to a database can increase the amount of disk space required to store the data.

Indexing can cause fragmentation: As records are added, modified, and deleted in a table, the data in the table and the associated index can become fragmented. This can slow down read and write operations, as the database system needs to search through a larger number of data blocks to find the relevant records.

In database management systems, there are several types of indexes, each with its own benefits and trade-offs. The most commonly used types of indexes are:

Clustered Index: A clustered index is an index in which the data in the table is physically sorted on the basis of the indexed column. It determines the order in which the rows of a table are stored on disk. A table can have only one clustered index. Clustered indexes are useful for tables that are frequently queried using range searches or for tables that are frequently updated in a sequential order.

Non-Clustered Index: A non-clustered index is an index that is created on a separate structure from the data and is linked to the data using a pointer. Non-clustered indexes can be created on one or more columns of a table. Non-clustered indexes are useful for tables that are frequently queried for individual values or for tables that are frequently updated in a random order.

Unique Index: A unique index is an index that ensures that the indexed column or columns contain only unique values. A table can have multiple unique indexes. Unique indexes are useful for tables that require data integrity and uniqueness of values in a column or set of columns.

Bitmap Index: A bitmap index is a type of index that uses a bitmap to represent the presence or absence of a value in a column. Bitmap indexes are useful for columns that have a small number of distinct values and for tables with a large number of rows.

Full-Text Index: A full-text index is an index that is used for searching text-based data such as documents or web pages. Full-text indexes are useful for tables that contain large amounts of textual data.

When deciding which type of index to use, consider the following factors:

Cardinality: The number of distinct values in a column or set of columns. If a column has high cardinality, a unique or non-clustered index might be more appropriate. If a column has low cardinality, a bitmap index might be more appropriate.

Frequency of Querying: The frequency with which a table is queried for a particular column or set of columns. If a table is frequently queried for a range of values in a column or set of columns, a clustered index might be more appropriate. If a table is frequently queried for individual values in a column or set of columns, a non-clustered index might be more appropriate.

Frequency of Updating: The frequency with which a table is updated. If a table is frequently updated, a non-clustered index might be more appropriate, as clustered indexes can slow down update operations.

Data Size: The size of the data set. Full-text indexes might be more appropriate for tables that contain large amounts of textual data, while bitmap indexes might be more appropriate for tables with a large number of rows.

Overall, the choice of index type depends on the specific requirements of the database and the queries that will be performed on it.

[Table of Contents](#Data-Warehousing-Architecture)

## What is an Integrity Constrains?
An integrity constraint is a declarative way to define a business rule for a column of a table.

[Table of Contents](#Data-Warehousing-Architecture)

## What are Clusters?
Clusters are groups of one or more tables physically stores together to share common columns and are often used together.

[Table of Contents](#Data-Warehousing-Architecture)

## What are the different types of Segments?
Data Segment,
Index Segment,
Rollback Segment and Temporary Segment.

[Table of Contents](#Data-Warehousing-Architecture)

## Explain the Relationship among database and Table Space and Data File?
Each database logically divided into one or more table spaces one or more data files are explicitly created for each table space.

[Table of Contents](#Data-Warehousing-Architecture)

## What is an Index Segment?
Each Index has an Index segment that stores all of its data.

[Table of Contents](#Data-Warehousing-Architecture)

## What are the Referential Actions supported by Foreign Key integrity constraint?
Update And Delete Restrict - A referential integrity rule that disallows the update or deletion of referenced data. DELETE Cascade - When a referenced row is deleted all associated dependent rows are deleted.

[Table of Contents](#Data-Warehousing-Architecture)

## Do you View contain Data?
Views do not contain or store data.

[Table of Contents](#Data-Warehousing-Architecture)

## What is the use of Control File?
When an instance of an ORACLE database is started, its control file is used to identify the database and redo log files that must be opened for database operation to proceed. It is also used in database recovery.

[Table of Contents](#Data-Warehousing-Architecture)

## Can Objects of the same Schema reside in different Table Spaces?
Yes

[Table of Contents](#Data-Warehousing-Architecture)

## Can a Table Space hold objects from different Schemes?
Yes

[Table of Contents](#Data-Warehousing-Architecture)

## Can a View based on another View?
Yes

[Table of Contents](#Data-Warehousing-Architecture)

## What is a full Backup?
A full backup is an operating system backup of all data files, on- line redo log files and control file that constitute ORACLE database and the parameter.

[Table of Contents](#Data-Warehousing-Architecture)

## What is Mirrored on line redo Log?
A mirrored on-line redo log consists of copies of on-line redo log files physically located on separate disks; changes made to one member of the group are made to all members.

[Table of Contents](#Data-Warehousing-Architecture)

## What is Partial Backup?
A Partial Backup is any operating system backup short of a full backup, taken while the database is open or shut down.

[Table of Contents](#Data-Warehousing-Architecture)

## What is Restricted Mode of Instance Startup?
An instance can be started in (or later altered to be in) restricted mode so that when the database is open connections are limited only to those whose user accounts have been granted the RESTRICTED SESSION system privilege.

[Table of Contents](#Data-Warehousing-Architecture)

## What are the steps involved in Database Shutdown?
Close the Database; Dismount the Database and Shutdown the Instance.

[Table of Contents](#Data-Warehousing-Architecture)

## What are the advantages of Operating a Database in archivelog mode over operating it in no Archivelog Mode?
Complete database recovery from disk failure is possible only in ARCHIVELOG mode. Online database backup is possible only in ARCHIVELOG mode.

[Table of Contents](#Data-Warehousing-Architecture)

## What are the different modes of Mounting a Database with the Parallel Server?
Exclusive Mode If the first instance that mounts a database does so in exclusive mode, only that Instance can mount the database. Parallel Mode If the first instance that mounts a database is started in parallel mode, other instances that are started in parallel mode can also mount the database.

[Table of Contents](#Data-Warehousing-Architecture)

## Can Full Backup be performed when the Database is Open?
No

[Table of Contents](#Data-Warehousing-Architecture)

## What are the steps involved in instance Recovery?
Rolling forward to recover data that has not been recorded in data files yet has been recorded in the on-line redo log, including the contents of rollback segments. Rolling back transactions that have been explicitly rolled back or have not been committed as indicated by the rollback segments regenerated in step a.
1) Releasing any resources (locks) held by transactions in process at the time of the failure.
2) Resolving any pending distributed transactions undergoing a two-phase commit at the time of the instance failure.

[Table of Contents](#Data-Warehousing-Architecture)

## What are the steps involved in Database Startup?
Start an instance, Mount the Database and Open the Database.

[Table of Contents](#Data-Warehousing-Architecture)

## Which parameter specified in the Default Storage Clause of create Tablespace cannot be Altered after creating the Table Space?
All the default storage parameters defined for the table space can be changed using the ALTER TABLESPACE command. When objects are created their INITIAL and MINEXTENS values cannot be changed.

[Table of Contents](#Data-Warehousing-Architecture)

## What is Online redo Log?
The On-line Redo Log is a set of tow or more on-line redo files that record all committed changes made to the database. Whenever a transaction is committed, the corresponding redo entries temporarily stores in redo log buffers of the SGA are written to an on-line redo log file by the background process LGWR. The on-line redo log files are used in cyclical fashion.

[Table of Contents](#Data-Warehousing-Architecture)

## What is Log Switch?
The point at which ORACLE ends writing to one online redo log file and begins writing to another is called a log switch.

[Table of Contents](#Data-Warehousing-Architecture)

## What is Dimensional Modelling?
Dimensional Modelling is a design concept used by many data warehouse designers to build their data warehouse. In this design model all the data is stored in two types of tables - Facts table and Dimension table. Fact table contains the facts/measurements of the business and the dimension table contains the context of measurements i.e., the dimensions on which the facts are calculated.

[Table of Contents](#Data-Warehousing-Architecture)

## What are the difference between snow Flake and Star Schema and what are situations where Snow Flake Schema is better than Star Schema to use and when the opposite is True?
Star schema contains the dimension tables mapped around one or more fact tables. It is a renormalized model and no need to use complicated joins. Also queries results fast.Snowflake schema: It is the normalized form of Star schema. It contains in-depth joins, because the tables are split in to many pieces. We can easily do modification directly in the tables. We have to use complicated joins, since we have more tables.There will be some delay in processing the query.

[Table of Contents](#Data-Warehousing-Architecture)

## What is a Cube in Data Warehousing concept?
Cubes are logical representation of multidimensional data. The edge of the cube contains dimension members and the body of the cube contains data values.

[Table of Contents](#Data-Warehousing-Architecture)

## What are the differences between Star and Snowflake Schema?
Star schema: A single fact table with N number of DimensionSnowflake schema: Any dimensions with extended dimensions are known as snowflake schema.

[Table of Contents](#Data-Warehousing-Architecture)

## What are Data Marts?
Data marts are smaller subsets of a larger data warehouse that are designed to serve the needs of specific business units or departments within an organization. They contain a subset of the data warehouse's data, typically focused on a particular subject area or business function, and are optimized for querying and reporting on that data.

Unlike a full data warehouse, which can contain vast amounts of historical and transactional data, data marts are designed to be more agile and flexible, with a smaller and more focused set of data that can be quickly and easily analyzed by business users.

Data marts can be built in different ways, such as by extracting data from the larger data warehouse, or by sourcing data directly from operational systems. They can also be designed using different data modeling approaches, such as dimensional modeling or relational modeling, depending on the specific requirements of the business users and the data being analyzed.

Overall, data marts provide a way for organizations to provide more targeted and efficient access to data, enabling business users to make better and more informed decisions based on the specific data they need.

[Table of Contents](#Data-Warehousing-Architecture)

## What is the Data Type of the Surrogate Key?
There is no data type for a Surrogate Key. Requirement of a surrogate Key: UNIQUE Recommended data type of a Surrogate key is NUMERIC.
A surrogate key is a unique identifier assigned to each record in a table to serve as the primary key. Surrogate keys are not derived from the data and have no meaning to the business or end users. Instead, they are system-generated keys used to uniquely identify records in a table.

In a data warehouse, surrogate keys are commonly used to improve performance and simplify ETL processes. Since the data in a data warehouse is typically sourced from multiple systems with different data structures and keys, surrogate keys provide a consistent way to join data from different sources. Additionally, using surrogate keys can eliminate the need to use natural keys, which can be lengthy and complex, and may contain sensitive information.

Surrogate keys also provide a way to handle changes to the source data without affecting the data warehouse. If a record in the source system is updated, a new record is typically inserted into the data warehouse with a new surrogate key, rather than updating the existing record. This maintains the integrity of the data in the data warehouse and ensures that historical data is not lost or overwritten.

Overall, surrogate keys play an important role in the design and implementation of a data warehouse, providing a reliable and efficient way to manage and integrate data from multiple sources.

[Table of Contents](#Data-Warehousing-Architecture)

## What are Fact and Dimension and Measure?
In a data warehouse, a fact is a measurable event that has occurred in the business, such as a sale, a customer interaction, or a shipment. A fact table contains the measurements or metrics associated with the event, such as quantity, amount, price, and cost. Each row in the fact table represents a specific event that has occurred in the business, and the values in the table correspond to the dimensions associated with that event.

Dimensions provide context and additional information about the event captured in the fact table. Dimensions are typically descriptive attributes, such as time, geography, product, or customer, that provide additional information about the event. Dimension tables contain the attributes related to the dimension, and each row in the dimension table represents a unique value of that attribute.

Measures are the numeric values in the fact table that represent the quantitative aspect of the event captured. Measures can be aggregated and analyzed to gain insights into the business operations. Examples of measures include sales revenue, cost of goods sold, and profit margin.

Overall, facts, dimensions, and measures form the basis of a multidimensional data model, which is used to organize and analyze large volumes of data in a data warehouse. By separating the event data into facts and dimensions, and by aggregating the measures, analysts can quickly and easily analyze the data to gain insights into the business operations.


[Table of Contents](#Data-Warehousing-Architecture)

## What are the different Types of Data Warehousing?
Types of data warehousing are:
1. Enterprise Data warehousing
2. ODS (Operational Data Store)
3. Data Mart

[Table of Contents](#Data-Warehousing-Architecture)

## What do you mean by Static and Local Variable?
Static variable is not created on function stack but is created in the initialized data segment and hence the variable can be shared across the multiple call of the same function. Usage of static variables within a function is not thread safe.On the other hand, local variable or auto variable is created on function stack and valid only in the context of the function call and is not shared across function calls.

[Table of Contents](#Data-Warehousing-Architecture)

## What is a Source Qualifier?
When you add a relational or a flat file source definition to a mapping, you need to connect it to a Source Qualifier transformation. The Source Qualifier represents the rows that the Informatica Server reads when it executes a session.

## What are the Steps to Build the Data Warehouse?
Gathering business requirements>>Identifying Sources>>Identifying Facts>>Defining Dimensions>>Define Attributes>>Redefine Dimensions / Attributes>>Organize Attribute Hierarchy>>Define Relationship>>Assign Unique Identifiers.

[Table of Contents](#Data-Warehousing-Architecture)

## What is the advantages Data Mining over Traditional approaches?
Data Mining is used for the estimation of future. For example, if we take a company/business organization, by using the concept of Data Mining, we can predict the future of business in terms of Revenue (or) Employees (or) Customers (or) Orders etc.Traditional approaches use simple algorithms for estimating the future. However, it does not give accurate results when compared to Data Mining.

[Table of Contents](#Data-Warehousing-Architecture)

## What is the difference between View and Materialized View?
The key difference between a view and a materialized view is that a view is a virtual table that needs to be recalculated every time it is queried, while a materialized view is a physical table that is pre-calculated and stored in the database. This means that querying a materialized view can be much faster than querying a regular view, especially if the query involves complex calculations or joins.

However, since a materialized view contains data that is derived from one or more underlying tables, it needs to be refreshed periodically to ensure that the data is up-to-date. Refreshing a materialized view can be an expensive operation, especially if the underlying data changes frequently.

[Table of Contents](#Data-Warehousing-Architecture)

## What is the main difference between Inmon and Kimball Philosophies of Data Warehousing?
The Inmon and Kimball philosophies of data warehousing are two different approaches to designing and building a data warehouse.

The Inmon approach, also known as the top-down approach, is a more traditional approach that focuses on building a centralized data warehouse that is the single source of truth for an organization. The data warehouse is designed to support enterprise-wide reporting and analysis by integrating data from multiple sources and transforming it into a consistent, standardized format. In the Inmon approach, the data warehouse is built first and then smaller data marts are created for specific business units or departments.

The Kimball approach, also known as the bottom-up approach, is a more iterative approach that focuses on building data marts for specific business units or departments first, and then integrating them into a larger data warehouse over time. The data marts are designed to meet the specific reporting and analysis needs of each business unit or department and are built using a dimensional model that is optimized for querying and reporting.

The main difference between the two approaches is the order in which the data warehouse and data marts are built. The Inmon approach builds a centralized data warehouse first, which requires a significant investment in time and resources before it can deliver value to the organization. The Kimball approach, on the other hand, delivers value more quickly by building data marts first and integrating them into a larger data warehouse over time.

Another difference between the two approaches is the modeling technique used. The Inmon approach uses a normalized data model, which is optimized for data consistency and integrity, while the Kimball approach uses a dimensional data model, which is optimized for querying and reporting.

Ultimately, the choice between the two approaches depends on the specific needs and goals of the organization. The Inmon approach may be more suitable for organizations that require a centralized view of data across the entire enterprise, while the Kimball approach may be more suitable for organizations that need to deliver value quickly to specific business units or departments.

[Table of Contents](#Data-Warehousing-Architecture)

## What is Junk Dimension and what is the difference between Junk Dimension and Degenerated Dimension?
 junk dimension is a small table that is created to store low cardinality and unrelated attributes that do not fit well in the fact or dimension tables. These attributes may not be meaningful on their own, but when combined, they can provide useful information for analysis. Junk dimensions are typically used to simplify the fact table by removing the need for multiple columns for these low cardinality attributes.

On the other hand, a degenerate dimension is a dimension that is derived from a fact table and has no independent existence of its own. It is essentially a single column that represents a unique identifier for a transaction, such as an invoice number or a sales order number. Degenerate dimensions are used to track the status or history of a transaction and are often used as a reference in fact tables.

The main difference between a junk dimension and a degenerate dimension is that a junk dimension contains unrelated attributes that do not fit well in the fact or dimension tables, while a degenerate dimension represents a single column in a fact table that serves as a unique identifier for a transaction. Additionally, junk dimensions are typically created as separate tables, while degenerate dimensions are derived from fact tables.

In summary, a junk dimension is a small table that stores low cardinality and unrelated attributes, while a degenerate dimension is a single column that serves as a unique identifier for a transaction and is derived from a fact table.
Sure, here are examples for both a junk dimension and a degenerate dimension:

Example of a Junk Dimension:

Suppose you have a fact table that tracks sales transactions and you want to include information about the payment method used for each transaction. You could create a separate table called PaymentMethod that includes the following columns:

PaymentMethodKey (surrogate key)
PaymentMethodType (e.g. credit card, debit card, cash, check)
PaymentMethodIssuer (e.g. Visa, Mastercard, American Express)
You could then add a column to the fact table called PaymentMethodKey, which references the PaymentMethod table. This allows you to track the payment method used for each transaction without cluttering the fact table with multiple columns for each payment method attribute.

Example of a Degenerate Dimension:

Suppose you have a fact table that tracks sales transactions and you want to include information about the sales order number for each transaction. You could add a column to the fact table called SalesOrderNumber, which serves as a unique identifier for each transaction. This column would not be joined to a separate dimension table, as it represents a single column in the fact table and has no independent existence of its own. The SalesOrderNumber column could be used to track the status or history of each transaction, such as the date it was created or the date it was shipped.

[Table of Contents](#Data-Warehousing-Architecture)

## Why Fact Table is in Normal Form?
The fact table consists of the Index keys of the dimension/look up tables and the measures. So whenever we have the keys in a table. That it implies that the table is in the normal form.

[Table of Contents](#Data-Warehousing-Architecture)

## What is difference between Er Modeling and Dimensional Modeling?
ER modeling (Entity-Relationship modeling) and dimensional modeling are two different approaches to database modeling, each suited to a different type of data storage and analysis.

ER modeling is a modeling technique that focuses on representing real-world entities, relationships, and attributes in a database. ER models are used in operational databases, where the focus is on transaction processing and maintaining data integrity. In ER modeling, the data is normalized to reduce redundancy and to ensure that each piece of information is stored in only one place. ER models are designed to support transaction processing and are optimized for insert, update, and delete operations.

Dimensional modeling, on the other hand, is a modeling technique that focuses on representing data in a way that is optimized for query and analysis. Dimensional models are used in data warehousing and business intelligence applications, where the focus is on analyzing data to gain insights and make decisions. In dimensional modeling, data is organized into dimensions and facts. Dimensions are the attributes that describe the data, such as time, location, and product. Facts are the measures or metrics that are being analyzed, such as sales, revenue, or profit. Dimensional models are designed to support reporting and analysis and are optimized for query performance.

The main difference between ER modeling and dimensional modeling is the focus of the modeling technique. ER modeling is focused on data integrity and transaction processing, while dimensional modeling is focused on query and analysis performance. Additionally, ER models tend to be highly normalized, with the goal of reducing data redundancy and ensuring data consistency, while dimensional models are typically denormalized to improve query performance and make it easier to analyze data.

In summary, ER modeling is a technique for representing real-world entities, relationships, and attributes in a database, while dimensional modeling is a technique for organizing data into dimensions and facts that is optimized for query and analysis performance.

[Table of Contents](#Data-Warehousing-Architecture)

## What is Conformed Fact?
Conformed dimensions are the dimensions, which can be used across multiple Data Marts in combination with multiple facts tables accordingly.

[Table of Contents](#Data-Warehousing-Architecture)

## What are the Methodologies of Data Warehousing?
Every company has methodology of their own. However, to name a few SDLC Methodology, AIM methodology is standard used.

[Table of Contents](#Data-Warehousing-Architecture)

## What is Bus Schema?
BUS Schema is composed of a master suite of confirmed dimension and standardized definition if facts.

[Table of Contents](#Data-Warehousing-Architecture)

## What is Data Warehousing Hierarchy?
Hierarchies are logical structures that use ordered levels as a means of organizing data. A hierarchy can be used to define data aggregation. For example, in a time dimension, a hierarchy might aggregate data from the month level to the quarter level to the year level. A hierarchy can also be used to define a navigational drill path and to establish a family structure.Within a hierarchy, each level is logically connected to the levels above and below it. Data values at lower levels aggregate into the data values at higher levels. A dimension can be composed of more than one hierarchy. For example, in the product dimension, there might be two hierarchies--one for product categories and one for product suppliers.Dimension hierarchies also group levels from general to granular. Query tools use hierarchies to enable you to drill down into your data to view different levels of granularity. This is one of the key benefits of a data warehouse.When designing hierarchies, you must consider the relationships in business structures. Hierarchies impose a family structure on dimension values. For a particular level value, a value at the next higher level is its parent, and values at the next lower level are its children. These familial relationships enable analysts to access data quickly.

[Table of Contents](#Data-Warehousing-Architecture)

## What are Data Validation Strategies for Data Mart Validation after loading process?
Data validation is to make sure that the loaded data is accurate and meets the business requirements. Strategies are different methods followed to meet the validation requirements.

[Table of Contents](#Data-Warehousing-Architecture)

## What are the Data Types present in Bo and what happens if we implement View in the Designer N Report?
Three different data types: Dimensions, Measure, and DetailView is nothing but an alias and it can be used to resolve the loops in the universe.

[Table of Contents](#Data-Warehousing-Architecture)

## What is Surrogate Key and where we use it?
Surrogate key is a substitution for the natural primary key.It is just a unique identifier or number for each row that can be used for the primary key to the table. The only requirement for a surrogate primary key is that it is unique for each row in the table.
Data warehouses typically use a surrogate, (also known as artificial or identity key), key for the dimension tables primary keys. They can use Info sequence generator, or Oracle sequence, or SQL Server Identity values for the surrogate key.
It is useful because the natural primary key (i.e. Customer Number in Customer table) can change and this makes updates more difficult.
Some tables have columns such as AIRPORT_NAME OR CITY_NAME which are stated as the primary keys (according to the business users) but ,not only can these change, indexing on a numerical value is probably better and you could consider creating a surrogate key called, say, AIRPORT_ID. This would be internal to the system and as far as the client is concerned, you may display only the AIRPORT_NAME.

[Table of Contents](#Data-Warehousing-Architecture)

## What is a Linked Cube?
Linked cube in which a sub-set of the data can be analyzed into detail. The linking ensures that the data in the cubes remain consistent.

[Table of Contents](#Data-Warehousing-Architecture)

## What is meant by Metadata in Context of a Data Warehouse and how it is important?
Metadata is the data about data; Business Analyst or data modeler usually capture information about data - the source (where and how the data is originated), nature of data (char, varchar, nullable, existence, valid values etc) and behavior of data (how it is modified / derived and the life cycle) in data dictionary.
Metadata is also presented at the Datamart level, subsets, fact and dimensions, ODS etc. For a DW user, metadata provides vital information for analysis / DSS.

[Table of Contents](#Data-Warehousing-Architecture)

## What are the possible Data Marts in Retail Sales?
Product information and sales information.

[Table of Contents](#Data-Warehousing-Architecture)

## What are the various Etl Tools in the market?
Various ETL tools used in market are Informatica Data Stage Oracle Warehouse Builder Ab Initio Data Junction.

[Table of Contents](#Data-Warehousing-Architecture)

## What is Dimensional Modeling?
Dimensional Modeling is a design concept used by many data warehouse designers to build their data warehouse. In this design model all the data is stored in two types of tables - Facts table and Dimension table. Fact table contains the facts/measurements of the business and the dimension table contains the context of measurements i.e., the dimensions on which the facts are calculated.Dimension modeling is a method for designing data warehouse. Three types of modeling are there
1. Conceptual modeling
2. Logical modeling
3. Physical modeling.

[Table of Contents](#Data-Warehousing-Architecture)

## What is Vldb?
The perception of what constitutes a VLDB continues to grow. A one-terabyte database would normally be considered VLDB.Degenerate dimension: it does not have any link with dimensions and it will not have any attribute.

[Table of Contents](#Data-Warehousing-Architecture)

## What is Degenerate Dimension Table?
Degenerate Dimensions: If a table contains the values, which r neither dimension nor measures is called degenerate dimensions. For example invoice id, employee no.A degenerate dimension is data that is dimensional in nature but stored in a fact table.

[Table of Contents](#Data-Warehousing-Architecture)

## What is Er Diagram?
The Entity-Relationship (ER) model was originally proposed in 1976 as a way to unify the network and relational database views. Simply stated the ER model is a conceptual data model that views the real world as entities and relationships. A basic component of the model is the Entity-Relationship diagram, which is used to visually represent data objects. Since Chen wrote his paper the model has been extended and today it is commonly used for database design for the database designer, the utility of the ER model is: it maps well to the relational model. The constructs used in the ER model can easily be transformed into relational tables. It is simple and easy to understand with a minimum of training. Therefore, the database designer to communicate the design to the end user can use the model. In addition, the model can be used as a design plan by the database developer to implement a data model in specific database management software.

[Table of Contents](#Data-Warehousing-Architecture)

## What is the difference between Snowflake and Star Schema and what are situations where Snowflake Schema is better than Star Schema?
Star schema contains the dimension tables mapped around one or more fact tables.It is a renormalized model and no need to use complicated joins. Also Queries results fast.Snowflake schema is the normalized form of Star schema. It contains in-depth joins, because the tables are spited in to many pieces. We can easily do modification directly in the tables.We have to use complicated joins, since we have more tables. There will be some delay in processing the Query.

[Table of Contents](#Data-Warehousing-Architecture)

## Can a Dimension Table contain numeric values?
Yes. However, those data type will be char (only the values can numeric/char).Yes, dimensions even contain numerical because these are descriptive elements of our business.

[Table of Contents](#Data-Warehousing-Architecture)

## What is Hybrid Slowly Changing Dimension?
Hybrid SCDs are combination of both SCD 1 and SCD 2.It may happen that in a table, some columns are important and we need to track changes for them i.e. capture the historical data for them whereas in some columns even if the data changes, we don't care.For such tables we implement Hybrid SCDs, where in some columns are Type 1 and some are Type 2.You can add that it is not an intelligent key but similar to a sequence number and tied to a timestamp typically!

[Table of Contents](#Data-Warehousing-Architecture)

## How many clustered indexes can you create for a table in Dwh and in case Of Truncate and Delete command what happens to table which has unique Id.
You can have only one clustered index per table. If you use delete command, you can rollback... it fills your redo log files.
If you do not want records, you may use truncate command, which will be faster and does not fill your redo log file.

[Table of Contents](#Data-Warehousing-Architecture)

## What is Loop in Data Warehousing?
In DWH loops may exist between the tables. If loops exist, then query generation will take more time, because more than one path is available. It creates ambiguity also. Loops can be avoided by creating aliases of the table or by context.
Example: 4 Tables - Customer, Product, Time, Cost forming a close loop. Create alias for the cost to avoid loop.

[Table of Contents](#Data-Warehousing-Architecture)

## What is an Error Log Table in Informatica occurs and how to maintain it in mapping?
Error Log in Informatica is a one of output file created by Informatica Server while running the session for error messages. It is created in Informatica home directory.

[Table of Contents](#Data-Warehousing-Architecture)

## What is Drilling Across?
Drill across corresponds to switching from 1 classification in 1 dimension to a different classification in different dimension.

[Table of Contents](#Data-Warehousing-Architecture)

## Where the Cache Files stored?
Caches are stored in Repository.

[Table of Contents](#Data-Warehousing-Architecture)

## What is Dimension Modeling?
A logical design technique that seeks to present the data in a standard, intuitive framework that allows for high-performance access. There are different data modeling concepts like ER Modeling (Entity Relationship modeling), DM (Dimensional modeling), Hierarchal Modeling, Network modeling. However, popular are ER and DM only.

[Table of Contents](#Data-Warehousing-Architecture)

## What is Data Cleaning?
Data cleaning is a self-explanatory term. Most of the data warehouses in the world source data from multiple systems - systems that were created long before data warehousing was well understood, and hence without the vision to consolidate the same in a single repository of information. In such a scenario, the possibilities of the following are there:
► Missing information for a column from one of the data sources;
► Inconsistent information among different data sources;
► Orphan records;
► Outlier data points;
► Different data types for the same information among various data sources, leading to improper conversion;
► Data breaching business rules
In order to ensure that the data warehouse is not infected by any of these discrepancies, it is important to cleanse the data using a set of business rules, before it makes its way into the data warehouse.

[Table of Contents](#Data-Warehousing-Architecture)

## Can you explain the Hierarchies Level Data Warehousing?
In Data warehousing, levels are columns available in dimension table. Levels are having attributes. Hierarchies are used for navigational purpose; there are two types of Hierarchies. You can define hierarchies in top down or bottom up.
1. Natural Hierarchy: Best example is Time Dimension - Year, Month, Day etc. In natural Hierarchy definite relationship exists between each level
2. Navigational Hierarchy: You can have levels like
   Ex - Production cost of Product, Sales Cost of Product.
   Ex - Lead Time defined to procure, Actual Procurement time,
   In this, two levels need not to have relationship. This Hierarchy is created for navigational purpose.

[Table of Contents](#Data-Warehousing-Architecture)

## Can you explain about Core Dimension and Balanced Dimension and Dirty Dimension?
Dirty Dimension is nothing but Junk Dimensions. Core Dimensions are dedicated for a fact table or Data mart. Conformed Dimensions are used across fact tables or Data marts.

[Table of Contents](#Data-Warehousing-Architecture)

## What is Core Dimension?
Core Dimension is a Dimension table, which is used dedicated for single fact table or Datamart. Conform Dimension is a Dimension table which is used across fact tables or Data marts.

[Table of Contents](#Data-Warehousing-Architecture)

## After we create a Scd Table can we use that Particular Dimension as a Dimension Table for Star Schema?
Yes.

[Table of Contents](#Data-Warehousing-Architecture)

## Suppose you are filtering rows using a Filter Transformation and only rows meet the condition pass to the Target so tell me where rows will go that does not meet condition.
Informatica filter transformation default value is 1 i.e. true. If you place a break point on filter transformation and run the mapping in a debugger mode, you will find these values 1 or 0 for each row passing through filter. If you change 0 to 1, the particular row will be passed to next stage.

[Table of Contents](#Data-Warehousing-Architecture)

## What is Galaxy Schema?
Galaxy schema is also known as fact constellation scheme. It requires no of fact tables to share dimension tables. In data, wares housing mainly the people are using the conceptual hierarchy.

[Table of Contents](#Data-Warehousing-Architecture)

## Briefly state different between Data Ware House and Data Mart?
Data warehouse is made up of many datamarts. DWH contain many subject areas. However, data mart focuses on one subject area generally. E.g. If there will be DHW of bank then there can be one data mart for accounts, one for Loans etc. This is high-level definitions.

[Table of Contents](#Data-Warehousing-Architecture)

## What is MetaData?
Metadata is data about data. E.g. if in data mart we are receiving any file. Then metadata will contain information like how many columns, file is fix width/limited, ordering of fields, data types of field etc.

[Table of Contents](#Data-Warehousing-Architecture)

## What is the Definitions for Datawarehose And Datamart?
Datamart is subset of Datawarehouse we can say a datamart is collection of individual departmental information...Where as datawarehouse in collection of datamart.
Data mart is a single subject and datawarehouse is a integration of multiple subjects.

[Table of Contents](#Data-Warehousing-Architecture)

## What is Data Validation Strategies for Data Mart validation after Loading Process
Data validation is generally done manually in DWH in this case if source and TGT are relational you need to create SQL scripts to validate source and target data and if source isFlat file or non relational database you can use excel if data is very less or create dummy tables to validate your ETL code.

[Table of Contents](#Data-Warehousing-Architecture)

## What is Data Mining?
Data Mining is the process of analyzing data from different perspectives and summarizing it into useful information.

[Table of Contents](#Data-Warehousing-Architecture)

## What is Ods?
ODS is abbreviation of Operational Data Store. A database structure that is a repository for near real-time operational data rather than long term trend data. The ODS may further become the enterprise shared operational database, allowing operational systems that are being re-engineered to use the ODS as there operation databases.

[Table of Contents](#Data-Warehousing-Architecture)

## What is Etl?
ETL is abbreviation of extract, transform, and load. ETL is software that enables businesses to consolidate their disparate data while moving it from place to place, and it doesn’t really matter that that data is in different forms or formats. The data can come from any source.ETL is powerful enough to handle such data disparities. First, the extract function reads data from a specified source database and extracts a desired subset of data. Next, the transform function works with the acquired data – using rules orlookup tables, or creating combinations with other data – to convert it to the desired state. Finally, the load function is used to write the resulting data to a target database.

[Table of Contents](#Data-Warehousing-Architecture)

## Is Oltp Database is design optimal for Data Warehouse?
No. OLTP database tables are normalized, and it will add additional time to query to return results. Additionally, OLTP database is smaller, and it does not contain longer period (many years) data, which needs to be analyzed. A OLTP system is basically ER model and not Dimensional Model. If a complex query is executed on a OLTP system, it may cause a heavy overhead on the OLTP server that will affect the normal business processes.

[Table of Contents](#Data-Warehousing-Architecture)

## If Denormalized is improves Data Warehouse Processes and why Fact Table is in Normal Form?
Foreign keys of facts tables are primary keys of Dimension tables. It is clear that fact table contains columns which are primary key to other table that itself make normal form table.

[Table of Contents](#Data-Warehousing-Architecture)

## What are Lookup Tables?
A lookup table is the table placed on the target table based upon the primary key of the target, it just updates the table by allowing only modified (new or updated) records based on lookup condition.

[Table of Contents](#Data-Warehousing-Architecture)

## What are Aggregate Tables?
Aggregate table contains the summary of existing warehouse data which is grouped to certain levels of dimensions. It is always easy to retrieve data from aggregated tables than visiting original table which has million records. Aggregate tables reduces the load in the database server and increases the performance of the query and can retrieve the result quickly.

[Table of Contents](#Data-Warehousing-Architecture)

## What is real time Datawarehousing?
Data warehousing captures business activity data. Real-time data warehousing captures business activity data as it occurs. As soon as the business activity is complete and there is data about it, the completed activity data flows into the data warehouse and becomes available instantly.

[Table of Contents](#Data-Warehousing-Architecture)

## What are Conformed Dimensions?
Conformed dimensions mean the exact same thing with every possible fact table to which they are joined. They are common to the cubes.

[Table of Contents](#Data-Warehousing-Architecture)

## How do you load the Time Dimension?
Time dimensions are usually loaded by a program that loops through all possible dates that may appear in the data. 100 years may be represented in a time dimension, with one row per day.

[Table of Contents](#Data-Warehousing-Architecture)

## What is a Level of Granularity of a Fact Table?
Level of granularity means level of detail that you put into the fact table in a data warehouse. Level of granularity would mean what detail are you willing to put for each transactional fact.

[Table of Contents](#Data-Warehousing-Architecture)

## What are Non additive facts?
Non-additive facts are facts that cannot be summed up for any of the dimensions present in the fact table. However, they are not considered as useless. If there is changes in dimensions the same facts can be useful.

[Table of Contents](#Data-Warehousing-Architecture)

## What is Factless Facts Table?
A fact table which does not contain numeric fact columns it is called factless facts table.

[Table of Contents](#Data-Warehousing-Architecture)

## Explain about Olap?
OLAP is known as online analytical processing which provides answers to queries which are multi dimensional in nature. It composes relational reporting and data mining for providing solutions to business intelligence. This term OLAP is created from the term OLTP.

[Table of Contents](#Data-Warehousing-Architecture)

## Explain about the Functionality of Olap?
Hyper cube or multidimensional cube forms the core of OLAP system. This consists of measures which are arranged according to dimensions. Hyper cube Meta data is created by star or snow flake schema of tables in RDBMS. Dimensions are extracted from dimension table and measures from the fact table.

[Table of Contents](#Data-Warehousing-Architecture)

## Explain about Molap?
Classic form of OLAP is known as MOLAP and it is often called as OLAP. Simple database structures such as time period, product, location, etc. are used. Functioning of each and every dimension or data structure is defined by one or more hierarchies.

[Table of Contents](#Data-Warehousing-Architecture)

## Explain about Rolap?
Functioning of ROLAP occurs simultaneously with relational databases. Data and tables are stored as relational tables. To hold new information or data new tables are created. Functioning of ROLAP depends upon specialized schema design.

[Table of Contents](#Data-Warehousing-Architecture)

## Explain about Aggregations?
OLAP can process complex queries and give the output in less than 0.1 seconds, for it to achieve such a performance OLAP uses aggregations. Aggregations are built by aggregating and changing the data along the dimensions. Possible combination of aggregations can be determined by the combination possibilities of dimension granularities.

[Table of Contents](#Data-Warehousing-Architecture)

## Explain about the View Selection problem?
Often calculating all the data is not possible by aggregations for this reason some complex data problems are solved. In order to determine which data should be solved and calculated, developers use View selection application. This solution is often used to reduce calculation problem.

[Table of Contents](#Data-Warehousing-Architecture)

## Explain about the role of Bitmap Indexes to solve Aggregation Problems?
Bitmaps are very useful in start schema to join large databases to small databases. Answer queries and bit arrays are used to perform logical operations on the databases. Bit map indexes are very efficient in handling Gender differentiation; also repetitive tasks are performed with much larger efficiency.

[Table of Contents](#Data-Warehousing-Architecture)

## Explain about Encoding Technique used in Bitmaps Indexes?
Bitmaps commonly use one bitmap for every single distinct value. Number of bitmaps used can be reduced by opting for a different type of encoding. Space can be optimized but when a query is generated bitmaps have to be accessed.

[Table of Contents](#Data-Warehousing-Architecture)

## Explain about Binning?
Binning process is very useful to save space. Performance may vary depending upon the query generated sometimes solution to a query can come within few seconds and sometimes it may take longer time. Binning process holds multiple values in the same bin.

[Table of Contents](#Data-Warehousing-Architecture)

## Explain about Hybrid Olap?
When a database developer uses Hybrid OLAP it divides the data between relational and specialized storage. In some particular modifications a HOLAP database may store huge amounts of data in its relational tables. Specialized data storage is used to store data which is less detailed and more aggregate.

[Table of Contents](#Data-Warehousing-Architecture)

## Explain about Shared Features of Olap?
Shared implements most of the security features into OLAP. If multiple accesses are required admin can make necessary changes. The default security level for all OLAP products is read only. For multiple updates it is predominant to make necessary security changes.

[Table of Contents](#Data-Warehousing-Architecture)

## Explain about Analysis?
Analysis defines about the logical and statistical analysis required for an efficient output. This involves writing of code and performing calculations, but most part of these languages does not require complex programming language knowledge. There are many specific features which are included such as time analysis, currency translation, etc.

[Table of Contents](#Data-Warehousing-Architecture)

## Explain about Multidimensional Features present in Olap?
Multidimensional support is very essential if we are to include multiple hierarchies in our data analysis. Multidimensional feature allows a user to analyze business and organization. OLAP efficiently handles support for multidimensional features.

[Table of Contents](#Data-Warehousing-Architecture)

## Explain about the Database Marketing Application of Olap?
Database marketing tool or application helps a user or marketing professional in determining the right tool or strategy for his valuable add campaign. This tool collects data from all sources and gives relevant information the specialist with their add campaign. It gives a complete picture to the developer.

[Table of Contents](#Data-Warehousing-Architecture)

## Compare Data Warehouse Database and Oltp Database.
The data warehouse and the OLTP data base are bothrelational databases. However, the objectives of both these databases are different.
The OLTP database records transactions in real time and aims to automate clerical data entry processes of a business entity. Addition, modification and deletion of data in the OLTP database is essential and the semantics of the applicationused in the front end impact on the organization of the data in the database.
The data warehouse on the other hand does not cater to real time operational requirements of the enterprise. It is more a storehouse of current and historical data and may alsocontain data extracted from external data sources.

[Table of Contents](#Data-Warehousing-Architecture)

## What is the difference between Etl Tool and Olap Tool and what are various Etl in the Market?
ETL is an extraction,transformation,loading tool i.e u can extract , u can transform using different transformations available in tool and aggreagte the data. The output of thisETL tool is used as input to OLAP tool.
OLAP is online analytical process, where u can get online reports after doing some joines,creating some cubes

ETL tools in market
1 INFORMATICA-- univeral tool ,good market
2 ABINITO -- fastest loading tool,very good market
3 DATASTAGE-- difficult work, no good market
4 BODI-- good market
5 ORACLE WAREHOUSE BUILDER-- good market.

[Table of Contents](#Data-Warehousing-Architecture)

## Steps in building the Data Model.
While ER model lists and defines the constructs required to build a data model, there is no standard process for doing so. Some methodologies, such as IDEFIX, specify a bottom-up.

[Table of Contents](#Data-Warehousing-Architecture)

## Why is Data Modeling important?
Data modeling is probably the most labor-intensive and time-consuming part of the development process. Why bother especially if you are pressed for time? A common.

[Table of Contents](#Data-Warehousing-Architecture)

## What Type of Indexing Mechanism do we need use for a typical Datawarehouse?
On the fact table it is best to use bitmap indexes. Dimension tables can use bitmap and/or the other types of clustered/non-clustered, unique/non-unique indexes.
To my knowledge, SQLServer does not support bitmap indexes. Only Oracle supports bitmaps.

[Table of Contents](#Data-Warehousing-Architecture)

## What are Semi additive and Factless Facts?
Semi-Additive: Semi-additive facts are facts that can be summed up for some dimensions in the fact table, but not the others. For example:
Current_Balance and Profit_Margin are the facts. Current_Balance is a semi-additive fact, as it makes sense to add them up for all accounts (what's the total current balance for all accounts in the bank?), but it does not make sense to add them up through time (adding up all current balances for a given account for each day of the month does not give us any useful information A factless fact table captures the many-to-many relationships between dimensions, but contains no numeric or textual facts. They are often used to record events or coverage information.
Common examples of factless fact tables include:

- Identifying product promotion events (to determine promoted products that didn?t sell)
- Tracking student attendance or registration events
- Tracking insurance-related accident events
- Identifying building, facility, and equipment schedules for a hospital or university.

[Table of Contents](#Data-Warehousing-Architecture)

## Is it correct develop a Data Mart using an Ods?
Yes it is correct to develop a Data Mart using an ODS.becoz ODS which is used to?store transaction data and few Days (less historical data) this is what datamart is required, so it is coct to develop datamart using ODS .

[Table of Contents](#Data-Warehousing-Architecture)

## Explain degenerated dimension.
A Degenerate dimension?is a?Dimension which has only a single attribute.
This dimension is typically represented as a single field in a fact table.
The data items thar are not facts and data items that do not fit into the existing dimensions are termed as Degenerate Dimensions.
Degenerate Dimensions are the fastest way to group similar transactions.
Degenerate Dimensions are used when fact tables represent transactional data.
They can be used as primary key for the fact table but they cannot act as foreign keys.

[Table of Contents](#Data-Warehousing-Architecture)

## What are the different methods of loading Dimension Tables?
Conventional Load:
Before loading the data, all the Table constraints will be checked against the data.
Direct load:(Faster Loading)
All the Constraints will be disabled. Data will be loaded directly.Later the data will be checked against the table constraints and the bad data won't be indexed.

[Table of Contents](#Data-Warehousing-Architecture)

## What are Slowly Changing Dimensions?
Dimensions that change over time are called Slowly Changing Dimensions. For instance, a product price changes over time; People change their names for some reason; Country and State names may change over time. These are a few examples of Slowly Changing Dimensions since some changes are happening to them over a period of time.
If the data in the Dimension table happen to change very rarely,then it is called as slowly changing dimension.
ex: changing the name and address of a person,which happens rerely.

[Table of Contents](#Data-Warehousing-Architecture)

## What is meant by Metadata in context of a Datawarehouse?
Metadata or Meta Data Metadata is data about data. Examples of metadata include data element descriptions, data type descriptions, attribute/property descriptions, range/domain descriptions, and process/method descriptions. The repository environment encompasses all corporate metadata resources: database catalogs, data dictionaries, and navigation services. Metadata includes things like the name, length, valid values, and description of a data element. Metadata is stored in a data dictionary and repository. It insulates the data warehouse from changes in the schema of operational systems. Metadata Synchronization The process of consolidating, relating and synchronizing data elements with the same or similar meaning from different systems. Metadata synchronization joins these differing elements together in the data warehouse to allow for easier access.

[Table of Contents](#Data-Warehousing-Architecture)

## What are Modeling Tools available in the Market
These tools are used for Data/dimension modeling
Oracle Designer
ERWin (Entity Relationship for windows)
Informatica (Cubes/Dimensions)
Embarcadero
Power Designer Sybase.

[Table of Contents](#Data-Warehousing-Architecture)

## What is the main difference between Schema in Rdbms and Schemas in Datawarehouse?
RDBMS Schema
* Used for OLTP systems
* Traditional and old schema
* Normalized
* Difficult to understand and navigate
* Cannot solve extract and complex problems
* Poorly modelled
  DWH Schema
* Used for OLAP systems
* New generation schema
* De Normalized
* Easy to understand and navigate
* Extract and complex problems can be easily solved
* Very good model.

[Table of Contents](#Data-Warehousing-Architecture)

## What is a general purpose Scheduling Tool?
The basic purpose of the scheduling tool in a DW Application is to streamline the flow of data from Source To Target at specific time or based on some condition.

[Table of Contents](#Data-Warehousing-Architecture)

## What is the need of Surrogate Key and why Primary Key not used as Surrogate Key?
Surrogate Key is an artificial identifier for an entity. In surrogate key values are generated by the system sequentially(Like Identity property in SQL Server and Sequence in Oracle). They do not describe anything. Primary Key is a natural identifier for an entity. In Primary keys all the values are entered manually by the user which are uniquely identified. There will be no repetition of data.

[Table of Contents](#Data-Warehousing-Architecture)

## What is Snow Flake Schema?
Snowflake schemas normalize dimensions to eliminate redundancy. That is, the dimension data has been grouped into multiple tables instead of one large table. For example, a product dimension table in a star schema might be normalized into a products table, a product_category table, and a product_manufacturer table in a snowflake schema. While this saves space, it increases the number of dimension tables and requires more foreign key joins. The result is more complex queries and reduced query performance.

[Table of Contents](#Data-Warehousing-Architecture)

## What is the difference between Oltp and Olap?
OLTP is nothing but OnLine Transaction Processing ,which contains a normalised tables and online data,which have frequent insert/updates/delete.

[Table of Contents](#Data-Warehousing-Architecture)

## How are the Dimension Tables designed?
Find where data for this dimension are located.
Figure out how to extract this data.
Determine how to maintain changes to this dimension.
Change fact table and DW population routines.

[Table of Contents](#Data-Warehousing-Architecture)

## What are the advantages Data Mining over traditional approaches?
Data Mining is used for?the estimation of future. For example,?if we take a company/business organization, by using the concept of Data Mining, we can predict the future of business interms of Revenue (or) Employees (or) Cutomers (or) Orders etc.
Traditional approaches use?simple algorithms?for estimating the future. But, it does not give accurate results when compared to Data Mining.

[Table of Contents](#Data-Warehousing-Architecture)

## Which automation tool is used in Data Warehouse testing?
No Tool testing in done in DWH, only manual testing is done.

[Table of Contents](#Data-Warehousing-Architecture)

## Give examples of Degenerated Dimensions.
Degenerated Dimension is a dimension key without corresponding dimension. Example:
In the PointOfSale Transaction Fact table, we have:
Date Key (FK), Product Key (FK), Store Key (FK), Promotion Key?(FP),?and POS Transaction Number?? Date Dimension corresponds to Date Key, Production Dimension corresponds to Production Key. In a traditional parent-child database, POS Transactional Number would be?the key to the transaction header record that contains all the info valid for the transaction as a whole, such as the transaction date and store?identifier.?But in this?dimensional model, we have already extracted this info into other dimension. Therefore, POS Transaction Number?looks like a dimension key in the fact table but does not have the corresponding dimension table.
Therefore, POS Transaction Number is a degenerated dimension.

[Table of Contents](#Data-Warehousing-Architecture)

## What is the datatype of the Surrogate Key?
Normally Surrogate keys are sequencers which keep on increasing with new records being injected into the table. The standard datatype is integer.

[Table of Contents](#Data-Warehousing-Architecture)

## What is the difference between scan Component and Rollup Component?
Rollup is for group by and Scan is for successive total. Basically, when we need to produce summary then we use scan. Rollup is used to aggregate data.

[Table of Contents](#Data-Warehousing-Architecture)

## What is M_dump?
m_dump command prints the data in a formatted way.

[Table of Contents](#Data-Warehousing-Architecture)

## What is Brodcasting and Replicate?
Broadcast - Takes data from multiple inputs, combines it and sends it to all the output ports.
Eg - You have 2 incoming flows (This can be data parallelism or component parallelism) on Broadcast component, one with 10 records & other with 20 records. Then on all the outgoing flows (it can be any number of flows) will have 10 + 20 = 30 records.
Replicate - It replicates the data for a particular partition and send it out to multiple out ports of the component, but maintains the partition integrity.
Eg - Your incoming flow to replicate has a data parallelism level of 2. with one partition having 10 recs & other one having 20 recs. Now suppose you have 3 output flos from replicate. Then each flow will have 2 data partitions with 10 & 20 records respectively.

[Table of Contents](#Data-Warehousing-Architecture)

## What is Local and Formal Parameter?
Two are graph level parameters but in local you need to initialize the value at the time of declaration where as globle no need to initialize the data it will promt at the time of running the graph for that parameter.

[Table of Contents](#Data-Warehousing-Architecture)

## What is the difference between Dml Expression and Xfr Expression?
The main difference b/w dml & xfr is that
DML represent format of the metadata.
XFR represent the tranform functions.which will contain business rules

[Table of Contents](#Data-Warehousing-Architecture)

## Have you used Rollup Component?
If the user wants to group the records on particular field values then rollup is best way to do that. Rollup is a multi-stage transform function and it contains the following mandatory functions.
1. initialise
2. rollup
3. finalise
   Also need to declare one temporary variable if you want to get counts of a particular group.

For each of the group, first it does call the initialise function once, followed by rollup function calls for each of the records in the group and finally calls the finalise function once at the end of last rollup call.

[Table of Contents](#Data-Warehousing-Architecture)

## What are Primary Keys and Foreign Keys?
In RDBMS the relationship between the two tables is represented as Primary key and foreign key relationship. Whereas the primary key table is the parent table and foreignkey table is the child table.The criteria for both the tables is there should be a matching column.

[Table of Contents](#Data-Warehousing-Architecture)

## What is Outer Join?
An outer join is used when one wants to select all the records from a port - whether it has satisfied the join criteria or not.

[Table of Contents](#Data-Warehousing-Architecture)

## What are Cartesian Joins?
A Cartesian join will get you a Cartesian product. A Cartesian join is when you join every row of one table to every row of another table. You can also get one by joining every row of a table to every row of itself.

[Table of Contents](#Data-Warehousing-Architecture)

## What is the purpose of having Stored Procedures in a Database?
Main Purpose of Stored Procedure for reduse the network trafic and all sql statement executing in cursor so speed too high.

[Table of Contents](#Data-Warehousing-Architecture)

## Why might you create a Stored Procedure with Recompile Option?
Recompile is useful when the tables referenced by the stored proc undergoes a lot of modification/ deletion/ addition of data. Due to the heavy modification activity the execute plan becomes outdated and hence the stored proc performance goes down. If we create the stored proc with recompile option, the sql server wont cache a plan for this stored proc and it will be recompiled every time it is run.

[Table of Contents](#Data-Warehousing-Architecture)

## What is Cursor?
The oracle engine uses work areas for internal processing in order to the execute sql statement is called cursor.There are two types of cursors like Implecit cursor and Explicit cursor.Implicit cursor is using for internal processing and Explicit cursor is using for user open for data required.

[Table of Contents](#Data-Warehousing-Architecture)

## Describe process steps you would perform when Defragmenting a Data Table and this table contains mission critical Data?
There are several ways to do this:
1) We can move the table in the same or other tablespace and rebuild all the indexes on the table.
   alter table move this activity reclaims the defragmented space in the table
   analyze table table_name compute statistics to capture the updated statistics.
   2)Reorg could be done by taking a dump of the table, truncate the table and import the dump back into the table.

[Table of Contents](#Data-Warehousing-Architecture)

## Explain the difference between Truncate and Delete Commands?
Truncate :
+ It is a DDL command, used to delete tables or clusters. Since it is a DDL command hence it is auto commit and Rollback can't be performed. It is faster than delete.

Delete:
+ It is DML command, generally used to delete a record, clusters or tables. Rollback command can be performed , in order to retrieve the earlier deleted things. To make deleted things permanently, "commit" command should be used.

[Table of Contents](#Data-Warehousing-Architecture)

## How would you find out whether Sql Query is using Indices you Expect?
Explain plan can be reviewed to check the execution plan of the query. This would guide if the expected indexes are used or not.

[Table of Contents](#Data-Warehousing-Architecture)

## What are the Security Level used in Bo?
We have securities in business objects
Like
1.Windows authentication
2.RDBMS securities
3.supervisor level securities, ie Username/ password.

[Table of Contents](#Data-Warehousing-Architecture)

## What are the Functional and Architectural differences between Business Objects and Web Intelligence Reports?
Functional differences
• Business objects, for building or accessing reports, needs to be installed on every pc. On the other hand, Web intelligence reports needs a browser and a URL of the server from where Business objects will be accessed.
• BOMain.key needs to be copied on every pc using BO client. This is not required for Web Intelligence Reports.
• Business objects expect you to use the same pc where they are installed. Web Intelligence reports can be accessed from anywhere, provided internet is available.

Architectural differences
For BO client, for sending info to BO Server BOMain.key, uses the key of the local drive. Once the information is sent, it is validated and checked into the repository upon which the user can access the BO services. On the other hand, Web Intelligence the web servers BOMain.key is used to check privilege of the user and then sending information to the BO Server BOMain.key.

[Table of Contents](#Data-Warehousing-Architecture)

## What is batch processing in Business Objects?
Batch processing can be used to schedule reports. Objects can be also be used for batch processing. Batch processing can be used to also select the objects to be processed. The batch can be run as a transaction in which if one process fails, the entire batch is rolled back or it can be run as a series of jobs.

[Table of Contents](#Data-Warehousing-Architecture)

## What is Data Cardinality?
Cardinality is the term used in database relations to denote the occurrences of data on either side of the relation.
There are 3 basic types of cardinality:
High data cardinality:
Values of a data column are very uncommon.
e.g.: email ids and the user names

Normal data cardinality:
Values of a data column are somewhat uncommon but never unique.
e.g.: A data column containing LAST_NAME (there may be several entries of the same last name)

Low data cardinality:
Values of a data column are very usual.
e.g.: flag statuses: 0/1

[Table of Contents](#Data-Warehousing-Architecture)

## What is Chained Data Replication?
In Chain Data Replication, the non-official data set distributed among many disks provides for load balancing among the servers within the data warehouse.
Blocks of data are spread across clusters and each cluster can contain a complete set of replicated data. All data block in every cluster is a unique permutation of the data in other clusters.
When a disk fails then all the calls made to the data in that disk are redirected to the other disks when the data has been replicated.
At times replicas and disks are added online without having to move around the data in the existing copy or affect the arm movement of the disk.
In load balancing, Chain Data Replication has multiple servers within the data warehouse share data request processing since data already have replicas in each server disk.

[Table of Contents](#Data-Warehousing-Architecture)

## Explain in brief various fundamental stages of Data Warehousing.
The following are the stages of data warehousing:
Offline Operational Database: It is the stage where copying the data off an operational system to another server where the report processing load against the copied data takes place and OS performance does not impact.
Offline Data Warehouse: In this stage, data warehouses are updated from data in the OS and the data of data warehouse is stored in a data structure that is designed for facilitating reports.
Real time Data Warehouse: The data warehouses are updated often when an OS performs a transaction.
Integrated Data Warehouse: The data warehouses are updated by OS, at the time of performing a transaction. Then transactions are generated which are passed back into the operational systems.

[Table of Contents](#Data-Warehousing-Architecture)

## What is the difference between Enterprise Data Warehouse and Data Warehouse?
Big Organizations have a lot of diversified sources of data.There might be a dataware house exclusively for transport and others for data related to the project the company runs.In such case the complete enterprise's(company's) date ware house is a big combination of all and is known the Enterprise data Warehouse(EDW)

[Table of Contents](#Data-Warehousing-Architecture)

## Give me any example of Semi and Non Additive Measures?
Semi-Additive: Semi-additive facts are facts that can be summed up for some dimensions in the fact table, but not the others. Non-Additive: Non-additive facts are facts that cannot be summed up for any of the dimensions present in the fact table. Current Balance and Profit Margin are the facts.Current Balance is a semi-additive fact, as it makes sense to add them up for all accounts (what's the total current balance for all accounts in the bank?), but it does not make sense to add them up through time (adding up all current balances for a given account for each day of the month does not give us any useful information). Profit Margin is a non-additive fact, for it does not make sense to add them up for the account level or the day level.

[Table of Contents](#Data-Warehousing-Architecture)

## What are the options in the Target Session of Update Strategy Transformations?
+ Insert
+ Delete
+ Update
+ Update as update
+ Update as insert
+ Update else insert
+ Truncate table

[Table of Contents](#Data-Warehousing-Architecture)

## What are the Various Types of Transformation?
Various types of transformation are: Aggregator Transformation, Expression Transformation, Filter
Transformation, Joiner Transformation, Lookup Transformation, Normalizer Transformation, Rank Transformation,
Router Transformation, Sequence Generator Transformation, Stored Procedure Transformation, Sorter
Transformation, Update Strategy Transformation, XML Source Qualifier Transformation, Advanced External
Procedure Transformation, External Transformation.

[Table of Contents](#Data-Warehousing-Architecture)

## What is the difference between Active Transformation and Passive Transformation?
An active transformation can change the number of rows that pass through it, but a passive transformation can not change the number of rows that pass through it.

[Table of Contents](#Data-Warehousing-Architecture)

## What is the difference between Static Cache and Dynamic Cache?
In case of dynamic cache, when we are inserting a new row it checks the lookup cache to see if it exists, if not inserts it into the target as well as the cache but in case of static cache the new row is written only in the target and not the lookup cache. The lookup cache remains static and does not change during the session but incase of dynamic cache the server inserts, updates in the cache during session.

[Table of Contents](#Data-Warehousing-Architecture)

## How do we join Two tables without Joiner or Sql Override?
We can join the tables using lookup transformation and making a cartesian product.

[Table of Contents](#Data-Warehousing-Architecture)

## Differences between Normalizer and Normalizer Transformation.
Normalizer: It is a transformation mainly using for cobol sources,
it's change the rows into columns and columns into rows
Normalization:To remove the redundancy and inconsistency.

What Is The Use Of Incremental Aggregation? Explain Me In Brief With An Example.
It's a session option. when the informatica server performs incremental aggr. it passes new source data through the mapping and uses historical cache data to perform new aggregation caluculations incrementaly. for performance we will use it.

[Table of Contents](#Data-Warehousing-Architecture)

## What is Business Intelligence?
Business Intelligence is a process for increasing the competitive advantage of a business by intelligent use of available data in decision-making.
The five key stages of Business Intelligence:
► Data Sourcing
► Data Analysis
► Situation Awareness
► Risk Assessment
► Decision Support.

[Table of Contents](#Data-Warehousing-Architecture)

## What is a Universe in Business Intelligence?
"universe" is a "Business object" terminology. Business objects also happens to be the name of the company. The universe is the interfacing layer between the client and the datawarehouse . The universe defines the relationship among the various tables in the datawarehouse.
Or Universe is a semantic layer between the database and the user interface (reports).

[Table of Contents](#Data-Warehousing-Architecture)

## What is Olap in Business Intelligence?
Online Analytical Processing, a category of software tools that provides analysis of data stored in a database. OLAP tools enable users to analyze different dimensions of multidimensional data. For example, it provides time series and trend analysis views. The chief component of OLAP is the OLAP server, which sits between a client and a database management systems (DBMS). The OLAP server understands how data is organized in the database and has special functions analyzing the data.
A good OLAP interface has writes an efficient sql and reads an accurate data from db.To design and architect having good knowledge on DB understanding the report requirements.

[Table of Contents](#Data-Warehousing-Architecture)

## What are various Modules in Business Objects Product?
► Business Objects Reporter
► Reporting & Analyzing tool
► Designer
► Universe creation
► database interaction
► connectivity
Supervisor - For Administrative purposes
Webintelligence - Access of report data through internet
BroadCast Agent - For scheduling the reports
Data Integrator - The ETL tool of Business Objects, designed to handle huge amounts of data.

[Table of Contents](#Data-Warehousing-Architecture)

## What is Olap Molap Rolap Dolap Holap?
OLAP - On-Line Analytical Processing.
Designates a category of applications and technologies that allow the collection, storage, manipulation and reproduction of multidimensional data, with the goal of analysis.

MOLAP - Multidimensional OLAP.
This term designates a cartesian data structure more specifically. In effect, MOLAP contrasts with ROLAP. Inb the former, joins between tables are already suitable, which enhances performances. In the latter, joins are computed during the request.
Targeted at groups of users because it's a shared environment. Data is stored in an exclusive server-based format. It performs more complex analysis of data.

DOLAP - Desktop OLAP.
Small OLAP products for local multidimensional analysis Desktop OLAP. There can be a mini multidimensional database (using Personal Express), or extraction of a datacube (using Business Objects).
Designed for low-end, single, departmental user. Data is stored in cubes on the desktop. It's like having your own spreadsheet. Since the data is local, end users dont have to worry about performance hits against the server.
ROLAP - Relational OLAP.
Designates one or several star schemas stored in relational databases. This technology permits multidimensional analysis with data stored in relational databases.
Used for large departments or groups because it supports large amounts of data and users.
HOLAP:Hybridization of OLAP, which can include any of the above.

[Table of Contents](#Data-Warehousing-Architecture)

## Why an Infocube has maximum of 16 dimensions?
It depends upon the Database limits provided to define the Foreign key constraint, e.g. in Sql Server 2005, the recommended max limit for foreign keys is 253, but you can define more.

[Table of Contents](#Data-Warehousing-Architecture)

## Name some standard Business Intelligence Tools in the Market?
Some standard Business Intelligence tools in the market According to their performance
► MICROSTRATEGY
► BUSINESS OBJECTS,CRYSTAL REPORTS
► COGNOS REPORT NET
► MS-OLAP SERVICES
Or
► Seagate Crystal report
► SAS
► Business objects
► Microstrategy
► Cognos
► Microsoft OLAP
Hyperion
Microsoft integrated services.

[Table of Contents](#Data-Warehousing-Architecture)

## What are Dashboards?
A management reporting tool to gauge how well the organization company is performing. It normally uses "traffic-lights" or "smiley faces" to determine the status.

[Table of Contents](#Data-Warehousing-Architecture)

## What is Hierarchy Relationship in a Dimension.
whether it is:
1. 1:1
2. 1:m
3. m:m
   1:M

[Table of Contents](#Data-Warehousing-Architecture)

## What are Adhoc reports and Static Reports?
Adhoc reports run in real time based on the input parameters provided by the user at the run time.In Microstrategy, adhoc reports are created using Prompts.
In static reports, users won't be provide any input parameters.These reports are usaully schedule to run overnight and ready to view immediatley in the mornings using cache.

[Table of Contents](#Data-Warehousing-Architecture)

## What is the Importance of Surrogate Key in Data Warehousing?
Surrogate Key is a Primary Key for a Dimension table. Most importance of using it is it is independent of underlying database. i.e Surrogate Key is not affected by the changes going on with a database.

[Table of Contents](#Data-Warehousing-Architecture)

## What is a Query?
A query is one or more statements that request data from a database. If the data is available, then the requested data returns in the form of a table which contains rows and columns. Queries are sent to the databases in a language called SQL. However, when using the Report Panel, SQL knowledge is not required.

[Table of Contents](#Data-Warehousing-Architecture)

## What are the Features of a Physical Data Model?
Features of a physical data model include:
+ Specification all tables and columns.
+ Foreign keys are used to identify relationships between tables.
+ Denormalization may occur based on user requirements.
+ Physical considerations may cause the physical data model to be quite different from the logical data model.
+ Physical data model will be different for different RDBMS. For example, data type for a column may be different between MySQL and SQL Server.

[Table of Contents](#Data-Warehousing-Architecture)

## What are the steps to design a Physical Model?
The steps for physical data model design are as follows:
Convert entities into tables.
Convert relationships into foreign keys.
Convert attributes into columns.
Modify the physical data model based on physical constraints / requirements.
IDMS (Integrated Database Management System) Interview Questions

[Table of Contents](#Data-Warehousing-Architecture)

## What are the Features of Conceptual Data Model?
Features of conceptual data model include:
Includes the important entities and the relationships among them.
No attribute is specified.
No primary key is specified.

[Table of Contents](#Data-Warehousing-Architecture)

## What are the difference between Logical Data Model and Conceptual Data Model?
In a logical data model, primary keys are present, whereas in a conceptual data model, no primary key is present.
In a logical data model, all attributes are specified within an entity. No attributes are specified in a conceptual data model.
Relationships between entities are specified using primary keys and foreign keys in a logical data model. In a conceptual data model, the relationships are simply stated, not specified, so we simply know that two entities are related, but we do not specify what attributes are used for this relationship.

[Table of Contents](#Data-Warehousing-Architecture)

## What are the steps to design Logical Data Model?
The steps for designing the logical data model are as follows:
+ Specify primary keys for all entities.
+ Find the relationships between different entities.
+ Find all attributes for each entity.
+ Resolve many-to-many relationships.
+ Normalization.

[Table of Contents](#Data-Warehousing-Architecture)

## What is Etl?
ETL stands for extraction transformation and loading
ETL provide developers with an interface for designing source-to-target mappings, transformation and job control parameter
* Extraction
  + Take data from an external source and move it to the warehouse pre-processor database
* Transformation
  + Transform data task allows point-to-point generating, modifying and transforming data
* Loading
  + Load data task adds records to a database table in a warehouse.

[Table of Contents](#Data-Warehousing-Architecture)

## What is a Three Tier Data Warehouse?
A data warehouse can be thought of as a three-tier system in which a middle system provides usable data in a secure way to end users. On either side of this middle system are the end users and the back-end data stores.

[Table of Contents](#Data-Warehousing-Architecture)

## What is Etl Process and how many steps Etl contains?
ETL is extraction , transforming , loading process , you will extract data from the source and apply the business role on it then you will load it in the target
The steps are :
+ 1-define the source (create the odbc and the connection to the source DB)
+ 2-define the target (create the odbc and the connection to the target DB)
+ 3-create the mapping ( you will apply the business role here by adding transformations , and define how the data flow will go from the source to the target )
+ 4-create the session (its a set of instruction that run the mapping )
+ 5-create the work flow (instruction that run the session)

[Table of Contents](#Data-Warehousing-Architecture)

## What is Full Load and Incremental or Refresh Load?
Full Load: completely erasing the contents of one or more tables and reloading with fresh data.
Incremental Load: applying ongoing changes to one or more tables based on a predefined schedule.

[Table of Contents](#Data-Warehousing-Architecture)

## What is a Staging Area?
Data staging is actually a collection of processes used to prepare source system data for loading a data warehouse. Staging includes the following steps:
Source data extraction, Data transformation (restructuring),
Data transformation (data cleansing, value transformations),
Surrogate key assignments

[Table of Contents](#Data-Warehousing-Architecture)

## Compare Etl and Manual Development.
ETL - The process of extracting data from multiple sources.(ex. flat files, XML, COBOL, SAP etc) is simpler with the help of tools.
Manual - Loading the data other than flat files and oracle table need more effort.
ETL - High and clear visibility of logic.
Manual - complex and not so user friendly visibility of logic.
ETL - Contains Meta data and changes can be done easily.
Manual - No Meta data concept and changes needs more effort.
ETL- Error handling, log summary and load progress makes life easier for developer and maintainer.
Manual - need maximum effort from maintenance point of view.
ETL - Can handle Historic data very well.
Manual - as data grows the processing time degrades.

[Table of Contents](#Data-Warehousing-Architecture)

## What is Rdbms?
Relational Data Base Management Systems (RDBMS) are database management systems that maintain data records and indices in tables. Relationships may be created and maintained across and among the data and tables. In a relational database, relationships between data items are expressed by means of tables. Interdependencies among these tables are expressed by data values rather than by pointers. This allows a high degree of data independence. An RDBMS has the capability to recombine the data items from different files, providing powerful tools for data usage.

[Table of Contents](#Data-Warehousing-Architecture)

## What is Normalization?
Database normalization is a data design and organization process applied to data structures based on rules that help build relational databases. In relational database design, the process of organizing data to minimize redundancy. Normalization usually involves dividing a database into two or more tables and defining relationships between the tables. The objective is to isolate data so that additions, deletions, and modifications of a field can be made in just one table and then propagated through the rest of the database via the defined relationships.

[Table of Contents](#Data-Warehousing-Architecture)

## What are different Normalization Forms?
+ 1NF: Eliminate Repeating Groups Make a separate table for each set of related attributes, and give each table a primary key. Each field contains at most one value from its attribute domain.
+ 2NF: Eliminate Redundant Data If an attribute depends on only part of a multi-valued key, remove it to a separate table.
+ 3NF: Eliminate Columns Not Dependent On Key If attributes do not contribute to a description of the key, remove them to a separate table. All attributes must be directly dependent on the primary key.
+ BCNF: Boyce-Codd Normal Form If there are non-trivial dependencies between candidate key attributes, separate them out into distinct tables.
+ 4NF: Isolate Independent Multiple Relationships No table may contain two or more 1:n or n:m relationships that are not directly related.
+ 5NF: Isolate Semantically Related Multiple Relationships There may be practical constrains on information that justify separating logically related many-to-many relationships.
+ ONF: Optimal Normal Form A model limited to only simple (elemental) facts, as expressed in Object Role Model notation.
+ DKNF: Domain-Key Normal Form A model free from all modification anomalies. Remember, these normalization guidelines are cumulative. For a database to be in 3NF, it must first fulfill all the criteria of a 2NF and 1NF database.

[Table of Contents](#Data-Warehousing-Architecture)

## What is Stored Procedure?
A stored procedure is a named group of SQL statements that have been previously created and stored in the server database. Stored procedures accept input parameters so that a single procedure can be used over the network by several clients using different input data. And when the procedure is modified, all clients automatically get the new version. Stored procedures reduce network traffic and improve performance. Stored procedures can be used to help ensure the integrity of the database.
e.g. sp_helpdb, sp_renamedb, sp_depends etc.

[Table of Contents](#Data-Warehousing-Architecture)

## What is Trigger?
A trigger is an SQL procedure that initiates an action when an event (INSERT, DELETE or UPDATE) occurs. Triggers are stored in and managed by the DBMS. Triggers are used to maintain the referential integrity of data by changing the data in a systematic fashion. A trigger cannot be called or executed; the DBMS automatically fires the trigger as a result of a data modification to the associated table. Triggers can be viewed as similar to stored procedures in that both consist of procedural logic that is stored at the database level. Stored procedures, however, are not event-drive and are not attached to a specific table as triggers are. Stored procedures are explicitly executed by invoking a CALL to the procedure while triggers are implicitly executed. In addition, triggers can also execute stored procedures.

[Table of Contents](#Data-Warehousing-Architecture)

## What is View?
A simple view can be thought of as a subset of a table. It can be used for retrieving data, as well as updating or deleting rows. Rows updated or deleted in the view are updated or deleted in the table the view was created with. It should also be noted that as data in the original table changes, so does data in the view, as views are the way to look at part of the original table. The results of using a view are not permanently stored in the database. The data accessed through a view is actually constructed using standard T-SQL select command and can come from one to many different base tables or even other views.

[Table of Contents](#Data-Warehousing-Architecture)

## Advantages of Dbms?
+ Redundancy is controlled.
+ Unauthorised access is restricted.
+ Providing multiple user interfaces.
+ Enforcing integrity constraints.
+ Providing backup and recovery.

[Table of Contents](#Data-Warehousing-Architecture)

## Disadvantage in File Processing System?
+ Data redundancy & inconsistency.
+ Difficult in accessing data.
+ Data isolation.
+ Data integrity.
+ Concurrent access is not possible.
+ Security Problems.

[Table of Contents](#Data-Warehousing-Architecture)

## Describe Three Levels of Data Abstraction?
There are three levels of abstraction:
Physical level: The lowest level of abstraction describes how data are stored.
Logical level: The next higher level of abstraction, describes what data are stored in database and what relationship among those data.
View level: The highest level of abstraction describes only part of entire database.
Oracle 11g Tutorial

[Table of Contents](#Data-Warehousing-Architecture)

## Define integrity Rules?
There are two Integrity rules.
+ Entity Integrity: States that “Primary key cannot have NULL value”.
+ Referential Integrity: States that “Foreign Key can be either a NULL value or should be Primary Key value of other relation.

[Table of Contents](#Data-Warehousing-Architecture)

## What is Extension and Intention?
+ Extension : It is the number of tuples present in a table at any instance. This is time dependent.
+ Intention : It is a constant value that gives the name, structure of table and the constraints laid on it.

[Table of Contents](#Data-Warehousing-Architecture)

## What is Data Independence?
Data independence means that “the application is independent of the storage structure and access strategy of data”. In other words, The ability to modify the schema definition in one level should not affect the schema definition in the next higher level.
Two types of Data Independence:
Physical Data Independence: Modification in physical level should not affect the logical level.
Logical Data Independence: Modification in logical level should affect the view level.

[Table of Contents](#Data-Warehousing-Architecture)

## What is a View and how it is related to Data Independence?
A view may be thought of as a virtual table, that is, a table that does not really exist in its own right but is instead derived from one or more underlying base table. In other words, there is no stored file that direct represents the view instead a definition of view is stored in data dictionary. Growth and restructuring of base tables is not reflected in views. Thus the view can insulate users from the effects of restructuring and growth in the database. Hence accounts for logical data independence.

[Table of Contents](#Data-Warehousing-Architecture)

## What is Data Model?
A collection of conceptual tools for describing data, data relationships data semantics and constraints.

[Table of Contents](#Data-Warehousing-Architecture)

## What is Object Oriented Model?
This model is based on collection of objects. An object contains values stored in instance variables with in the object. An object also contains bodies of code that operate on the object. These bodies of code are called methods. Objects that contain same types of values and the same methods are grouped together into classes.

[Table of Contents](#Data-Warehousing-Architecture)

## What is an Entity?
It is a 'thing' in the real world with an independent existence.

[Table of Contents](#Data-Warehousing-Architecture)

## What is an Entity Type?
It is a collection (set) of entities that have same attributes.

[Table of Contents](#Data-Warehousing-Architecture)

## What is an Entity Set?
It is a collection of all entities of particular entity type in the database.

[Table of Contents](#Data-Warehousing-Architecture)

## What is an Attribute?
It is a particular property, which describes the entity.

[Table of Contents](#Data-Warehousing-Architecture)

## What is Relation Schema and Relation?
A relation Schema denoted by R(A1, A2, …, An) is made up of the relation name R and the list of attributes Ai that it contains.
A relation is defined as a set of tuples. Let r be the relation which contains set tuples (t1, t2, t3, ..., tn). Each tuple is an ordered list of n-values t=(v1,v2, ..., vn).

[Table of Contents](#Data-Warehousing-Architecture)

## What is Degree of Relation?
It is the number of attribute of its relation schema.

[Table of Contents](#Data-Warehousing-Architecture)

## What is Relationship?
It is an association among two or more entities.

[Table of Contents](#Data-Warehousing-Architecture)

## What is Relationship Set?
The collection (or set) of similar relationships.

[Table of Contents](#Data-Warehousing-Architecture)

## What is Relationship Type?
Relationship type defines a set of associations or a relationship set among a given set of entity types.

[Table of Contents](#Data-Warehousing-Architecture)

## What Is DDL?
A data base schema is specifies by a set of definitions expressed by a special language called DDL.

[Table of Contents](#Data-Warehousing-Architecture)

## What Is Vdl?
It specifies user views and their mappings to the conceptual schema.  (view Definition Language)

[Table of Contents](#Data-Warehousing-Architecture)

## What is Sdl?
This language is to specify the internal schema. This language may specify the mapping between two schemas. (storage Definition Language)

[Table of Contents](#Data-Warehousing-Architecture)

## What Is Data Storage Definition Language?
The storage structures and access methods used by database system are specified by a set of definition in a special type of DDL called data storage-definition language.

[Table of Contents](#Data-Warehousing-Architecture)

## What Is Dml?
This language that enable user to access or manipulate data as organized by appropriate data model.
Procedural DML or Low level: DML requires a user to specify what data are needed and how to get those data.
Non-Procedural DML or High level: DML requires a user to specify what data are needed without specifying how to get those data.
(data Manipulation Language)

[Table of Contents](#Data-Warehousing-Architecture)

## What is Query Evaluation Engine?
It executes low-level instruction generated by compiler.

[Table of Contents](#Data-Warehousing-Architecture)

## What is Ddl Interpreter?
It interprets DDL statements and record them in tables containing metadata.

[Table of Contents](#Data-Warehousing-Architecture)

## What is Record at a time?
The Low level or Procedural DML can specify and retrieve each record from a set of records. This retrieve of a record is said to be Record-at-a-time.

[Table of Contents](#Data-Warehousing-Architecture)

## What is Set at a time or Set oriented?
The High level or Non-procedural DML can specify and retrieve many records in a single DML statement. This retrieve of a record is said to be Set-at-a-time or Set-oriented.

[Table of Contents](#Data-Warehousing-Architecture)

## What is Relational Algebra?
It is procedural query language. It consists of a set of operations that take one or two relations as input and produce a new relation.

[Table of Contents](#Data-Warehousing-Architecture)

## What is Relational Calculus?
It is an applied predicate calculus specifically tailored for relational databases proposed by E.F. Codd.
E.g. of languages based on it are DSL ALPHA, QUEL.

[Table of Contents](#Data-Warehousing-Architecture)

## How does Tuple oriented Relational calculus differ from Domain oriented Relational Calculus?
The tuple-oriented calculus uses a tuple variables i.e., variable whose only permitted values are tuples of that relation. E.g. QUEL
The domain-oriented calculus has domain variables i.e., variables that range over the underlying domains instead of over relation. E.g. ILL, DEDUCE.

[Table of Contents](#Data-Warehousing-Architecture)

## What is Functional Dependency?
A Functional dependency is denoted by X Y between two sets of attributes X and Y that are subsets of R specifies a constraint on the possible tuple that can form a relation state r of R. The constraint is for any two tuples t1 and t2 in r if t1[X] = t2[X] then they have t1[Y] = t2[Y]. This means the value of X component of a tuple uniquely determines the value of component Y.

[Table of Contents](#Data-Warehousing-Architecture)

## What is Multivalued Dependency?
Multivalued dependency denoted by X Y specified on relation schema R, where X and Y are both subsets of R, specifies the following constraint on any relation r of R: if two tuples t1 and t2 exist in r such that t1[X] = t2[X] then t3 and t4 should also exist in r with the following properties

t3[x] = t4[X] = t1[X] = t2[X]
t3[Y] = t1[Y] and t4[Y] = t2[Y]
t3[Z] = t2[Z] and t4[Z] = t1[Z]
where [Z = (R-(X U Y)) ]

[Table of Contents](#Data-Warehousing-Architecture)

## What is Lossless Join Property?
It guarantees that the spurious tuple generation does not occur with respect to relation schemas after decomposition.

[Table of Contents](#Data-Warehousing-Architecture)

## What Is 1 Nf?
The domain of attribute must include only atomic (simple, indivisible) values.

[Table of Contents](#Data-Warehousing-Architecture)

## What is Fully Functional Dependency?
It is based on concept of full functional dependency. A functional dependency X Y is full functional dependency if removal of any attribute A from X means that the dependency does not hold any more.

[Table of Contents](#Data-Warehousing-Architecture)

## What is 2nf?
A relation schema R is in 2NF if it is in 1NF and every non-prime attribute A in R is fully functionally dependent on primary key.

[Table of Contents](#Data-Warehousing-Architecture)

## What is 3nf?
A relation schema R is in 3NF if it is in 2NF and for every FD X A either of the following is true

X is a Super-key of R.
A is a prime attribute of R.
In other words, if every non prime attribute is non-transitively dependent on primary key.

What Is Bcnf (boyce-codd Normal Form)?
A relation schema R is in BCNF if it is in 3NF and satisfies an additional constraint that for every FD X A, X must be a candidate key.

[Table of Contents](#Data-Warehousing-Architecture)

## What is 4nf?
A relation schema R is said to be in 4NF if for every Multivalued dependency X Y that holds over R, one of following is true
X is subset or equal to (or) XY = R.
X is a super key.

[Table of Contents](#Data-Warehousing-Architecture)

## What is 5nf?
A Relation schema R is said to be 5NF if for every join dependency {R1, R2, ..., Rn} that holds R, one the following is true
Ri = R for some i.
The join dependency is implied by the set of FD, over R in which the left side is key of R.

[Table of Contents](#Data-Warehousing-Architecture)

## What is Domain key NF?
A relation is said to be in DKNF if all constraints and dependencies that should hold on the constraint can be enforced by simply enforcing the domain constraint and key constraint on the relation.

[Table of Contents](#Data-Warehousing-Architecture)

## What are Partial Alternate Artificial Compound and Natural Key?
+ Partial Key:
  + It is a set of attributes that can uniquely identify weak entities and that are related to same owner entity. It is sometime called as Discriminator.
+ Alternate Key:
  + All Candidate Keys excluding the Primary Key are known as Alternate Keys.
+ Artificial Key:
  + If no obvious key, either stand alone or compound is available, then the last resort is to simply create a key, by assigning a unique number to each record or occurrence. Then this is known as developing an artificial key.
+ Compound Key:
  + If no single data element uniquely identifies occurrences within a construct, then combining multiple elements to create a unique identifier for the construct is known as creating a compound key.
+ Natural Key:
  + When one of the data elements stored within a construct is utilized as the primary key, then it is called the natural key.

[Table of Contents](#Data-Warehousing-Architecture)

## What is Indexing and what are the different kinds of Indexing?
Indexing is a technique for determining how quickly specific data can be found.
Types:
+ Binary search style indexing
+ B-Tree indexing
+ Inverted list indexing
M+ emory resident table
+ Table indexing

[Table of Contents](#Data-Warehousing-Architecture)

## What is meant by Query Optimization?
The phase that identifies an efficient execution plan for evaluating a query that has the least estimated cost is referred to as query optimization.

[Table of Contents](#Data-Warehousing-Architecture)

## What is Join Dependency and Inclusion Dependency?
Join Dependency:
A Join dependency is generalization of Multivalued dependency.A JD {R1, R2, ..., Rn} is said to hold over a relation R if R1, R2, R3, ..., Rn is a lossless-join decomposition of R . There is no set of sound and complete inference rules for JD.
Inclusion Dependency:
An Inclusion Dependency is a statement of the form that some columns of a relation are contained in other columns. A foreign key constraint is an example of inclusion dependency.

[Table of Contents](#Data-Warehousing-Architecture)

## What is Durability in Dbms?
Once the DBMS informs the user that a transaction has successfully completed, its effects should persist even if the system crashes before all its changes are reflected on disk. This property is called durability.

[Table of Contents](#Data-Warehousing-Architecture)

## What do you mean by Atomicity and Aggregation?
Atomicity:
Either all actions are carried out or none are. Users should not have to worry about the effect of incomplete transactions. DBMS ensures this by undoing the actions of incomplete transactions.
Aggregation:
A concept which is used to model a relationship between a collection of entities and relationships. It is used when we need to express a relationship among relationships.

[Table of Contents](#Data-Warehousing-Architecture)

## What is Phantom Deadlock?
In distributed deadlock detection, the delay in propagating local information might cause the deadlock detection algorithms to identify deadlocks that do not really exist. Such situations are called phantom deadlocks and they lead to unnecessary aborts.

[Table of Contents](#Data-Warehousing-Architecture)

## What is Checkpoint and when does it cccur?
A Checkpoint is like a snapshot of the DBMS state. By taking checkpoints, the DBMS can reduce the amount of work to be done during restart in the event of subsequent crashes.

[Table of Contents](#Data-Warehousing-Architecture)

## What are different Phases of Transaction?
Different phases are
Analysis phase
Redo Phase
Undo phase

[Table of Contents](#Data-Warehousing-Architecture)

## What do you mean by Flat File Database?
It is a database in which there are no programs or user access languages. It has no cross-file capabilities but is user-friendly and provides user-interface management.

[Table of Contents](#Data-Warehousing-Architecture)

## What is transparent Dbms?
It is one, which keeps its Physical Structure hidden from user.

[Table of Contents](#Data-Warehousing-Architecture)

## What do you mean by Correlated Subquery?
Subqueries, or nested queries, are used to bring back a set of rows to be used by the parent query. Depending on how the subquery is written, it can be executed once for the parent query or it can be executed once for each row returned by the parent query. If the subquery is executed for each row of the parent, this is called a correlated subquery.
A correlated subquery can be easily identified if it contains any references to the parent subquery columns in its WHERE clause. Columns from the subquery cannot be referenced anywhere else in the parent query. The following example demonstrates a non-correlated subquery.
E.g. Select * From CUST Where '10/03/1990' IN (Select ODATE From ORDER Where CUST.CNUM = ORDER.CNUM)

[Table of Contents](#Data-Warehousing-Architecture)

## What are the Primitive Operations common to all record management systems?
Addition, deletion and modification.

[Table of Contents](#Data-Warehousing-Architecture)

## What are Unary Operations in Relational Algebra?
PROJECTION and SELECTION.

## Are resulting Relations of Product and Join Operation the same?
No.
PRODUCT: Concatenation of every row in one relation with every row in another.
JOIN: Concatenation of rows from one relation and related rows from another.

[Table of Contents](#Data-Warehousing-Architecture)

## What is Rdbms Kernel?
Two important pieces of RDBMS architecture are the kernel, which is the software, and the data dictionary, which consists of the system-level data structures used by the kernel to manage the database
You might think of an RDBMS as an operating system (or set of subsystems), designed specifically for controlling data access; its primary functions are storing, retrieving, and securing data. An RDBMS maintains its own list of authorized users and their associated privileges; manages memory caches and paging; controls locking for concurrent resource usage; dispatches and schedules user requests; and manages space usage within its table-space structures.

[Table of Contents](#Data-Warehousing-Architecture)

## Name the Sub systems of Rdbms?
I/O, Security, Language Processing, Process Control, Storage Management, Logging and Recovery, Distribution Control, Transaction Control, Memory Management, Lock Management.

[Table of Contents](#Data-Warehousing-Architecture)

## What is Rowid?
The ROWID is a unique database-wide physical address for every row on every table. Once assigned (when the row is first inserted into the database), it never changes until the row is deleted or the table is dropped.
The ROWID consists of the following three components, the combination of which uniquely identifies the physical storage location of the row.
Oracle database file number, which contains the block with the rows
Oracle block address, which contains the row
The row within the block (because each block can hold many rows)
The ROWID is used internally in indexes as a quick means of retrieving rows with a particular key value. Application developers also use it in SQL statements as a quick way to access a row once they know the ROWID.

[Table of Contents](#Data-Warehousing-Architecture)

## What is Storage Manager?
It is a program module that provides the interface between the low-level data stored in database, application programs and queries submitted to the system.

[Table of Contents](#Data-Warehousing-Architecture)

## What is Buffer Manager?
It is a program module, which is responsible for fetching data from disk storage into main memory and deciding what data to be cache in memory.

[Table of Contents](#Data-Warehousing-Architecture)

## What is Transaction Manager?
It is a program module, which ensures that database, remains in a consistent state despite system failures and concurrent transaction execution proceeds without conflicting.

[Table of Contents](#Data-Warehousing-Architecture)

## What is File Manager?
It is a program module, which manages the allocation of space on disk storage and data structure used to represent information stored on a disk.

[Table of Contents](#Data-Warehousing-Architecture)

## What is Authorization and Integrity Manager?
It is the program module, which tests for the satisfaction of integrity constraint and checks the authority of user to access data.

[Table of Contents](#Data-Warehousing-Architecture)

## What are Stand alone procedures?
Procedures that are not part of a package are known as stand-alone because they independently defined. A good example of a stand-alone procedure is one written in a SQL*Forms application. These types of procedures are not available for reference from other Oracle tools. Another limitation of stand-alone procedures is that they are compiled at run time, which slows execution.

[Table of Contents](#Data-Warehousing-Architecture)

## What are the different methods of loading dimension tables?
There are two different methods to load data in dimension tables:
+ Conventional (slow): All the constraints and keys are validated against the information before, it is loaded, and this method data integrity is maintained.
+ Direct (fast): All the constraints and keys are disabled before the information is loaded. Once the information is loaded, it is validated against all the constraints and keys. If the data is found invalid, it is not contained in the index, and all the future processes are skipped in this data.

[Table of Contents](#Data-Warehousing-Architecture)

## Describe the foreign key columns in fact tables and dimension tables?
Foreign keys of dimension tables are the primary key of entity tables.
Foreign keys of fact tables are the primary key of dimension tables.

[Table of Contents](#Data-Warehousing-Architecture)
