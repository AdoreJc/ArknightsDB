# UIGachaBoxDrawEffectFloatPage

**Namespace:** `Torappu.Activity.Act3D0`


## Fields

- `Boolean _isSkippable`

- `UIBlurFloatPanel _backImage`

- `SkeletonGraphic _spineGraphic`

- `GameObject _effectHolder`

- `Boolean m_isBlurShown`

- `Options m_options`


## Methods

- `Boolean ShowIfNot(Options)`

- `Void OnClicked()`

- `TrackEntry _StartSpineAnimation()`

- `String _GetSkinNameFromStyle(Style)`

- `Void _SetActiveOfSpineAndEffect(Boolean)`

- `Boolean <>xLuaBaseProxy_FinishIfNot()`

- `Void <>xLuaBaseProxy_OnReset()`

- `Void <>xLuaBaseProxy_OnStart()`

- `Void <>xLuaBaseProxy_OnFinish()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act3D0
public class UIGachaBoxDrawEffectFloatPage : UIOneshotEffectFloatPanel, IHotfixable
{
	private Boolean _isSkippable; // 0x28
	private UIBlurFloatPanel _backImage; // 0x30
	private SkeletonGraphic _spineGraphic; // 0x38
	private GameObject _effectHolder; // 0x40
	private String[] _skinNameOfStyles; // 0x48
	private Boolean m_isBlurShown; // 0x50
	private Options m_options; // 0x58
	private static DelegateBridge __Hotfix0_ShowIfNot; // 0x0
	private static DelegateBridge __Hotfix0_FinishIfNot; // 0x8
	private static DelegateBridge __Hotfix0_OnClicked; // 0x10
	private static DelegateBridge __Hotfix0__StartSpineAnimation; // 0x18
	private static DelegateBridge __Hotfix0__GetSkinNameFromStyle; // 0x20
	private static DelegateBridge __Hotfix0__SetActiveOfSpineAndEffect; // 0x28
	private static DelegateBridge __Hotfix0_PlayEffect; // 0x30
	private static DelegateBridge __Hotfix0_OnReset; // 0x38
	private static DelegateBridge __Hotfix0_OnStart; // 0x40
	private static DelegateBridge __Hotfix0_OnFinish; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x322bbdc VA: 0x7595843bdc
	public Boolean ShowIfNot(Options options) { }
	// RVA: 0x322bc94 VA: 0x7595843c94
	public override Boolean FinishIfNot() { }
	// RVA: 0x322bd34 VA: 0x7595843d34
	public Void OnClicked() { }
	// RVA: 0x322bdb8 VA: 0x7595843db8
	private TrackEntry _StartSpineAnimation() { }
	// RVA: 0x322bec0 VA: 0x7595843ec0
	private String _GetSkinNameFromStyle(Style style) { }
	// RVA: 0x322bf78 VA: 0x7595843f78
	private Void _SetActiveOfSpineAndEffect(Boolean isActive) { }
	// RVA: 0x322c020 VA: 0x7595844020
	protected override IEnumerator PlayEffect() { }
	// RVA: 0x322c0f4 VA: 0x75958440f4
	protected override Void OnReset() { }
	// RVA: 0x322c164 VA: 0x7595844164
	protected override Void OnStart() { }
	// RVA: 0x322c218 VA: 0x7595844218
	protected override Void OnFinish() { }
	// RVA: 0x322c308 VA: 0x7595844308
	public Void .ctor() { }
	// RVA: 0x322c378 VA: 0x7595844378
	private Boolean <>xLuaBaseProxy_FinishIfNot() { }
	// RVA: 0x322c380 VA: 0x7595844380
	private Void <>xLuaBaseProxy_OnReset() { }
	// RVA: 0x322c388 VA: 0x7595844388
	private Void <>xLuaBaseProxy_OnStart() { }
	// RVA: 0x322c390 VA: 0x7595844390
	private Void <>xLuaBaseProxy_OnFinish() { }
}
```