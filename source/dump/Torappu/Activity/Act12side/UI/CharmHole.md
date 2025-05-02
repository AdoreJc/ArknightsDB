# CharmHole

**Namespace:** `Torappu.Activity.Act12side.UI`


## Fields

- `GameObject _empty`

- `GameObject _content`

- `Image _num`

- `Text _name`

- `Text _desc`

- `Image _icon`

- `Int32 m_idx`


## Methods

- `Void Flush(CharmItemData)`

- `Void SetIdx(Int32)`

- `Void EventOnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act12side.UI
public class CharmHole : MonoBehaviour, IHotfixable
{
	private GameObject _empty; // 0x18
	private GameObject _content; // 0x20
	private Image _num; // 0x28
	private Sprite[] _numSprites; // 0x30
	private Text _name; // 0x38
	private GameObject[] _rarities; // 0x40
	private Text _desc; // 0x48
	private Image _icon; // 0x50
	private Int32 m_idx; // 0x58
	public Action`1 onClick; // 0x60
	private static DelegateBridge __Hotfix0_Flush; // 0x0
	private static DelegateBridge __Hotfix0_SetIdx; // 0x8
	private static DelegateBridge __Hotfix0_EventOnClick; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x34520f8 VA: 0x7595a6a0f8
	public Void Flush(CharmItemData charmData) { }
	// RVA: 0x3452350 VA: 0x7595a6a350
	public Void SetIdx(Int32 idx) { }
	// RVA: 0x3452438 VA: 0x7595a6a438
	public Void EventOnClick() { }
	// RVA: 0x34524c0 VA: 0x7595a6a4c0
	public Void .ctor() { }
}
```