# UIAutochessEquipPair

**Namespace:** `Torappu.Battle.UI`


## Fields

- `Text _equipName`

- `Text _equipDescription`

- `Image _equipIcon`


## Methods

- `Void UpdateLayout(String, String, Sprite)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class UIAutochessEquipPair : MonoBehaviour, IHotfixable
{
	private Text _equipName; // 0x18
	private Text _equipDescription; // 0x20
	private Image _equipIcon; // 0x28
	private static DelegateBridge __Hotfix0_UpdateLayout; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x201fd90 VA: 0x7594637d90
	public Void UpdateLayout(String equipName, String equipDescription, Sprite icon) { }
	// RVA: 0x201fe70 VA: 0x7594637e70
	public Void .ctor() { }
}
```