# QCShopObjProgressViewModel

**Namespace:** `Torappu.UI.Shop`


## Fields

- `QCObject objData`

- `PlayerGoodProgressData playerShop`


## Properties

- `QCProgressGoodItem currentObj`


## Methods

- `QCProgressGoodItem get_currentObj()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class QCShopObjProgressViewModel
{
	public QCObject objData; // 0x10
	public List`1 progressData; // 0x18
	public PlayerGoodProgressData playerShop; // 0x20

	public QCProgressGoodItem currentObj { get; }

	// RVA: 0x244e840 VA: 0x7594a66840
	public QCProgressGoodItem get_currentObj() { }
	// RVA: 0x2450120 VA: 0x7594a68120
	public Void .ctor() { }
}
```