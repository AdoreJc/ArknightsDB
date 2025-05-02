# CharacterIllustItem

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `GameObject _unSelectedState`

- `GameObject _SelectedState`

- `GameObject _unActive`

- `GameObject _Active`

- `Image _illust`

- `Boolean m_cacheState`

- `Int32 m_state`


## Methods

- `Void OnClick()`

- `Void ApplyState(Int32)`

- `Void ApplyData(Boolean, Sprite, Boolean, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterIllustItem : MonoBehaviour
{
	private GameObject _unSelectedState; // 0x18
	private GameObject _SelectedState; // 0x20
	private GameObject _unActive; // 0x28
	private GameObject _Active; // 0x30
	private Image _illust; // 0x38
	public Action`1 OnSelect; // 0x40
	private Boolean m_cacheState; // 0x48
	private Int32 m_state; // 0x4c


	// RVA: 0x2d70f64 VA: 0x7595388f64
	public Void OnClick() { }
	// RVA: 0x2d70f84 VA: 0x7595388f84
	public Void ApplyState(Int32 index) { }
	// RVA: 0x2d70fec VA: 0x7595388fec
	public Void ApplyData(Boolean state, Sprite illust, Boolean selected, Int32 indexState) { }
	// RVA: 0x2d71084 VA: 0x7595389084
	public Void .ctor() { }
}
```