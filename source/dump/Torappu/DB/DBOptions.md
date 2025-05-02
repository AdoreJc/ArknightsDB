# DBOptions

**Namespace:** `Torappu.DB`


## Fields

- `Mode mode`

- `ConverterType defaultEncryptType`

- `ConverterType excelEncryptType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.DB
public class DBOptions : SingletonScriptableObject`1
{
	public Mode mode; // 0x18
	public ConverterType defaultEncryptType; // 0x1c
	public ConverterType excelEncryptType; // 0x20
	public AbstractTable[] tableAssets; // 0x28


	// RVA: 0x371da58 VA: 0x7595d35a58
	public static Boolean TryLoadDataVersionStr(out String dataVerStr) { }
	// RVA: 0x371dd30 VA: 0x7595d35d30
	public Void .ctor() { }
}
```