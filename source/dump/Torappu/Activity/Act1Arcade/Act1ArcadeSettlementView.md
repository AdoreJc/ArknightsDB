# Act1ArcadeSettlementView

**Namespace:** `Torappu.Activity.Act1Arcade`


## Fields

- `Boolean m_isInited`

- `Act1ArcadeSettlementStatusBaseView m_currentStatusView`

- `Act1ArcadeSettlementModel m_model`


## Methods

- `Void _InitIfNot()`

- `Void _InternalChangeViewStatus()`

- `Void _OnCloseClick()`

- `IEnumerator <>xLuaBaseProxy_ShowEnterEffectCoroutine()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Arcade
public class Act1ArcadeSettlementView : DynBattleFinishView
{
	private List`1 _statusViews; // 0x20
	private Boolean m_isInited; // 0x28
	private Dictionary`2 m_statusViewDict; // 0x30
	private Act1ArcadeSettlementStatusBaseView m_currentStatusView; // 0x38
	private Act1ArcadeSettlementModel m_model; // 0x40
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnInit; // 0x8
	private static DelegateBridge __Hotfix0_ShowEnterEffectCoroutine; // 0x10
	private static DelegateBridge __Hotfix0__InternalChangeViewStatus; // 0x18
	private static DelegateBridge __Hotfix0__OnCloseClick; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x3405214 VA: 0x7595a1d214
	private Void _InitIfNot() { }
	// RVA: 0x3405570 VA: 0x7595a1d570
	protected override Void OnInit() { }
	// RVA: 0x34055e8 VA: 0x7595a1d5e8
	public override IEnumerator ShowEnterEffectCoroutine() { }
	// RVA: 0x34056bc VA: 0x7595a1d6bc
	private Void _InternalChangeViewStatus() { }
	// RVA: 0x34058b4 VA: 0x7595a1d8b4
	private Void _OnCloseClick() { }
	// RVA: 0x3405918 VA: 0x7595a1d918
	public Void .ctor() { }
	// RVA: 0x3405a14 VA: 0x7595a1da14
	private IEnumerator <>xLuaBaseProxy_ShowEnterEffectCoroutine() { }
}
```