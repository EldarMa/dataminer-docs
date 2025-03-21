---
uid: Offload_database
---

# Offload database

If you set up your own offload or “central” database in your DataMiner System, that database will contain an offline copy of all (or some of) the data in the general DMA databases.

This offline database will then allow you, for instance, to produce all kinds of reports without interfering with the live DataMiner System. Even the most demanding database queries will not have any impact on the performance of your DMAs.

This section consists of the following topics:

- [Setting up an offload database](xref:Setting_up_an_offload_database)

- [Structure of the offload database](xref:Structure_of_the_offload_database)

- [Configuring data offloads](xref:Configuring_data_offloads)

- [How DataMiner offloads data](xref:How_DataMiner_offloads_data)

> [!TIP]
> See also:
> [What happens if an offload database ...](xref:Databases1#what-happens-if-an-offload-database)

> [!NOTE]
> From DataMiner 10.2.0/10.1.1 onwards, it is possible to offload data to a file in the local system cache folder instead of to an offload database. You can do so by going to System Center > *Database* > *Offload* and selecting *File* in the drop-down box at the top. Below this, you can then configure the data offloads (see [Configuring data offloads](xref:Configuring_data_offloads)) and set a maximum size for the combined offload files.
>
