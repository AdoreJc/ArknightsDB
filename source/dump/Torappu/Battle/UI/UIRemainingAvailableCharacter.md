# UIRemainingAvailableCharacter

**Namespace:** `Torappu.Battle.UI`


## Fields

- `Text _cntLabel`

- `Int32 m_count`


## Properties

- `Boolean isActive`

- `Int32 count`


## Methods

- `Boolean get_isActive()`

- `Void set_count(Int32)`

- `Void OnInit()`

- `Void UpdateVisibility()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class UIRemainingAvailableCharacter : MonoBehaviour, IHotfixable
{
	private Text _cntLabel; // 0x18
	private Int32 m_count; // 0x20
	private static DelegateBridge __Hotfix0_get_isActive; // 0x0
	private static DelegateBridge __Hotfix0_set_count; // 0x8
	private static DelegateBridge __Hotfix0_OnInit; // 0x10
	private static DelegateBridge __Hotfix0_UpdateVisibility; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public Boolean isActive { get; }
	public Int32 count { set; }

	// RVA: 0x2082a30 VA: 0x759469aa30
	public Boolean get_isActive() { }
	// RVA: 0x2082aac VA: 0x759469aaac
	public Void set_count(Int32 value) { }
	// RVA: 0x2082b94 VA: 0x759469ab94
	public Void OnInit() { }
	// RVA: 0x2082bfc VA: 0x759469abfc
	public Void UpdateVisibility() { }
	// RVA: 0x2082cd8 VA: 0x759469acd8
	public Void .ctor() { }
}
```