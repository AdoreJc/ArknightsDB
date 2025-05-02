# RecruitSpecialGachaUpCharListGroupView

**Namespace:** `Torappu.UI.Recruit`


## Fields

- `RarityRank _rarityRank`

- `SimpleLayoutContent _content`

- `Boolean m_hasInited`

- `Adapter m_adapter`


## Methods

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Recruit
public class RecruitSpecialGachaUpCharListGroupView : DataBinder`1, IHotfixable
{
	private RarityRank _rarityRank; // 0x20
	private SimpleLayoutContent _content; // 0x28
	private Boolean m_hasInited; // 0x30
	private List`1 m_cachedCharList; // 0x38
	private Adapter m_adapter; // 0x40
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2703fc0 VA: 0x7594d1bfc0
	public override Void OnValueChanged(RecruitSpecialGachaUpCharListProperty property) { }
	// RVA: 0x27040d0 VA: 0x7594d1c0d0
	private Void _InitIfNot() { }
	// RVA: 0x2704234 VA: 0x7594d1c234
	public Void .ctor() { }
}
```