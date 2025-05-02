# SquadFriendTabGroupView

**Namespace:** `Torappu.UI.Squad`


## Fields

- `SimpleLayoutContent _layoutContent`

- `Boolean m_inited`

- `Adapter m_adapter`

- `Int32 m_selectedIndex`


## Methods

- `Void _InitIfNot()`

- `Void ApplyData(List`1, ProfessionCategory, Action`1)`

- `Void UpdateSelectedItem(ProfessionCategory)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Squad
public class SquadFriendTabGroupView : MonoBehaviour, IHotfixable
{
	private SimpleLayoutContent _layoutContent; // 0x18
	private Boolean m_inited; // 0x20
	private Adapter m_adapter; // 0x28
	private List`1 m_professionList; // 0x30
	private List`1 m_paramList; // 0x38
	private Int32 m_selectedIndex; // 0x40
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_ApplyData; // 0x8
	private static DelegateBridge __Hotfix0_UpdateSelectedItem; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x23c950c VA: 0x75949e150c
	private Void _InitIfNot() { }
	// RVA: 0x23c9648 VA: 0x75949e1648
	public Void ApplyData(List`1 professionList, ProfessionCategory selectedProfession, Action`1 clickAction) { }
	// RVA: 0x23c9908 VA: 0x75949e1908
	public Void UpdateSelectedItem(ProfessionCategory professionCategory) { }
	// RVA: 0x23c9a40 VA: 0x75949e1a40
	public Void .ctor() { }
}
```