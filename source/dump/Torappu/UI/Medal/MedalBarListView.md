# MedalBarListView

**Namespace:** `Torappu.UI.Medal`


## Fields

- `MedalBarListItem _listItem`

- `Transform _container`

- `UIStringEvent _onClickEvent`

- `Boolean _showCountFlag`

- `Int32 countCache`

- `Single m_maxHeight`


## Methods

- `Void _InitCount(Int32)`

- `Void OnSetValue(Int32)`

- `Void Render(MedalListViewModel)`

- `Void SwitchProgressDisplay(Boolean)`

- `Void StopProgressAnim()`

- `Void ResetProgressAnim()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Medal
public class MedalBarListView : MonoBehaviour, IHotfixable
{
	private MedalBarListItem _listItem; // 0x18
	private Transform _container; // 0x20
	private UIStringEvent _onClickEvent; // 0x28
	private Boolean _showCountFlag; // 0x30
	private Int32 countCache; // 0x34
	public const Single ITEM_HEIGHT; // 0x0
	private List`1 m_listItem; // 0x38
	private Single m_maxHeight; // 0x40
	private static DelegateBridge __Hotfix0__InitCount; // 0x0
	private static DelegateBridge __Hotfix0_OnSetValue; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_SwitchProgressDisplay; // 0x18
	private static DelegateBridge __Hotfix0_StopProgressAnim; // 0x20
	private static DelegateBridge __Hotfix0_ResetProgressAnim; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x27a867c VA: 0x7594dc067c
	private Void _InitCount(Int32 count) { }
	// RVA: 0x27a45f4 VA: 0x7594dbc5f4
	public Void OnSetValue(Int32 value) { }
	// RVA: 0x27a6014 VA: 0x7594dbe014
	public Void Render(MedalListViewModel listViewModel) { }
	// RVA: 0x27a6f48 VA: 0x7594dbef48
	public Void SwitchProgressDisplay(Boolean showDetails) { }
	// RVA: 0x27a7018 VA: 0x7594dbf018
	public Void StopProgressAnim() { }
	// RVA: 0x27a6e90 VA: 0x7594dbee90
	public Void ResetProgressAnim() { }
	// RVA: 0x27a8880 VA: 0x7594dc0880
	public Void .ctor() { }
}
```