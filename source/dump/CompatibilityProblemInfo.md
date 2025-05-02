# CompatibilityProblemInfo

**Namespace:** ` `


## Fields

- `VersionInfo actualVersion`

- `String explicitProblemDescription`


## Methods

- `String DescriptionString()`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : 
public class CompatibilityProblemInfo
{
	public VersionInfo actualVersion; // 0x10
	public Int32[][] compatibleVersions; // 0x18
	public String explicitProblemDescription; // 0x20


	// RVA: 0x61f98dc VA: 0x75988118dc
	public String DescriptionString() { }
	// RVA: 0x61f9be4 VA: 0x7598811be4
	public Void .ctor() { }
}
```