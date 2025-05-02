# GlobalOptions

**Namespace:** `Torappu`


## Fields

- `String devVersion`

- `String dynamicConfigPath`

- `String crossThisBundleVersionToDeleteAllCachedFiles`

- `TextAsset cryptoPubKey`

- `TextAsset backupStringMap`

- `String _udtVersion`


## Properties

- `String funcVersion`

- `String udtVersion`


## Methods

- `String get_funcVersion()`

- `String get_udtVersion()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class GlobalOptions : SingletonScriptableObject`1
{
	public String devVersion; // 0x18
	public String dynamicConfigPath; // 0x20
	public String crossThisBundleVersionToDeleteAllCachedFiles; // 0x28
	public TextAsset cryptoPubKey; // 0x30
	public TextAsset backupStringMap; // 0x38
	private String _udtVersion; // 0x40

	public String funcVersion { get; }
	public String udtVersion { get; }

	// RVA: 0x2f36674 VA: 0x759554e674
	public String get_funcVersion() { }
	// RVA: 0x2f366c4 VA: 0x759554e6c4
	public String get_udtVersion() { }
	// RVA: 0x2f366cc VA: 0x759554e6cc
	public Void .ctor() { }
}
```