# BattleFinishDynState

**Namespace:** `Torappu.UI.BattleFinish`


## Fields

- `RectTransform _container`

- `IBattleFinishDynView m_battleFinishView`

- `Boolean m_isShowEffectEnd`


## Methods

- `Boolean _InitDynBattleFinish()`

- `IEnumerator _ShowEffectCoroutine()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.BattleFinish
public class BattleFinishDynState : UIPopupState
{
	private const Single PASTTIME; // 0x0
	private RectTransform _container; // 0x60
	private IBattleFinishDynView m_battleFinishView; // 0x68
	private Boolean m_isShowEffectEnd; // 0x70
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0__InitDynBattleFinish; // 0x10
	private static DelegateBridge __Hotfix0__ShowEffectCoroutine; // 0x18
	private static DelegateBridge __Hotfix0__TryGetBattleFinishView; // 0x20
	private static DelegateBridge __Hotfix0__TryGetActivityBattleFinishView; // 0x28
	private static DelegateBridge __Hotfix0__TryGetBusinessBattleFinishView; // 0x30
	private static DelegateBridge __Hotfix0__GetResPathByBusinessType; // 0x38
	private static DelegateBridge __Hotfix0__HasActivityOverrideBattleFinish; // 0x40
	private static DelegateBridge __Hotfix0__HasBusinessOverrideBattleFinish; // 0x48
	private static DelegateBridge __Hotfix0_HasDynOverrideBattleFinish; // 0x50
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x58
	private static DelegateBridge __Hotfix0_HideCoroutine; // 0x60
	private static DelegateBridge __Hotfix0_ShowImmediately; // 0x68
	private static DelegateBridge __Hotfix0_HideImmediately; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78


	// RVA: 0x2e85998 VA: 0x759549d998
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2e859fc VA: 0x759549d9fc
	protected override Void OnEnter() { }
	// RVA: 0x2e85a9c VA: 0x759549da9c
	private Boolean _InitDynBattleFinish() { }
	// RVA: 0x2e85ba4 VA: 0x759549dba4
	private IEnumerator _ShowEffectCoroutine() { }
	// RVA: 0x2e85c50 VA: 0x759549dc50
	private static Boolean _TryGetBattleFinishView(RectTransform container, out IBattleFinishDynView battleFinishView) { }
	// RVA: 0x2e85e24 VA: 0x759549de24
	private static Boolean _TryGetActivityBattleFinishView(RectTransform container, out IBattleFinishDynView battleFinishView) { }
	// RVA: 0x2e86138 VA: 0x759549e138
	private static Boolean _TryGetBusinessBattleFinishView(RectTransform container, out IBattleFinishDynView battleFinishView) { }
	// RVA: 0x2e86378 VA: 0x759549e378
	private static String _GetResPathByBusinessType(BusinessType businessType) { }
	// RVA: 0x2e85d44 VA: 0x759549dd44
	public static Boolean _HasActivityOverrideBattleFinish() { }
	// RVA: 0x2e86078 VA: 0x759549e078
	public static Boolean _HasBusinessOverrideBattleFinish() { }
	// RVA: 0x2e86568 VA: 0x759549e568
	public static Boolean HasDynOverrideBattleFinish() { }
	// RVA: 0x2e865dc VA: 0x759549e5dc
	protected override IEnumerator ShowCoroutine(TransactionContext context) { }
	// RVA: 0x2e86754 VA: 0x759549e754
	protected override IEnumerator HideCoroutine(TransactionContext context) { }
	// RVA: 0x2e868cc VA: 0x759549e8cc
	protected override Void ShowImmediately(TransactionContext context) { }
	// RVA: 0x2e869d8 VA: 0x759549e9d8
	protected override Void HideImmediately(TransactionContext context) { }
	// RVA: 0x2e86ae4 VA: 0x759549eae4
	public Void .ctor() { }
	// RVA: 0x2e86b54 VA: 0x759549eb54
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```