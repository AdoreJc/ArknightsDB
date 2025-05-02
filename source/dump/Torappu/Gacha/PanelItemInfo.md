# PanelItemInfo

**Namespace:** `Torappu.Gacha`


## Fields

- `Image _itemIcon`

- `Text _itemName`

- `Text _itemCount`

- `Text _getType`


## Methods

- `Void ApplyData(String, Int32, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Gacha
public class PanelItemInfo : MonoBehaviour
{
	private Image _itemIcon; // 0x18
	private Text _itemName; // 0x20
	private Text _itemCount; // 0x28
	private Text _getType; // 0x30


	// RVA: 0x36fb860 VA: 0x7595d13860
	public Void ApplyData(String itemId, Int32 itemCount, Boolean isNew) { }
	// RVA: 0x36fba90 VA: 0x7595d13a90
	public Void .ctor() { }
}
```