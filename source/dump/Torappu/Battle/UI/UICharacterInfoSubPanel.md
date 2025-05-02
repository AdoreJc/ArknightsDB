# UICharacterInfoSubPanel

**Namespace:** `Torappu.Battle.UI`


## Fields

- `UICharacterInfoPanel m_parent`


## Properties

- `UICharacterInfoPanel parentPanel`


## Methods

- `UICharacterInfoPanel get_parentPanel()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class UICharacterInfoSubPanel : MonoBehaviour, IHotfixable
{
	private UICharacterInfoPanel m_parent; // 0x18
	private static DelegateBridge __Hotfix0_get_parentPanel; // 0x0
	private static DelegateBridge __Hotfix0_OnInit; // 0x8
	private static DelegateBridge __Hotfix0_SetData; // 0x10
	private static DelegateBridge __Hotfix0_UpdateData; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	protected UICharacterInfoPanel parentPanel { get; }

	// RVA: 0x2038554 VA: 0x7594650554
	protected UICharacterInfoPanel get_parentPanel() { }
	// RVA: 0x2036dbc VA: 0x759464edbc
	public virtual Void OnInit(UICharacterInfoPanel parent) { }
	// RVA: 0x2036a74 VA: 0x759464ea74
	public virtual Void SetData(ObjectPtr`1 characterPtr, ModeType mode, Card card) { }
	// RVA: 0x2036b14 VA: 0x759464eb14
	public virtual Void UpdateData(ObjectPtr`1 characterPtr, ModeType mode, Card card) { }
	// RVA: 0x2036a00 VA: 0x759464ea00
	public Void .ctor() { }
}
```