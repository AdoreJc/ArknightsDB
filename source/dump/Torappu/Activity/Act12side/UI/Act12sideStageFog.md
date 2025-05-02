# Act12sideStageFog

**Namespace:** `Torappu.Activity.Act12side.UI`


## Fields

- `Text _textUnlockCount`

- `Text _textUnlockDesc`

- `Image _iconUnlockItem`

- `Button _btnUnlock`

- `UIAnimationLocation _dismissAnim`

- `GameObject _panelInfo`

- `String m_cachedStageId`

- `Param m_cachedParam`


## Methods

- `Void _FakeRenderViewOnStageNotOpen(StageFogInfo)`

- `Void _RenderViewImpl(Param)`

- `Void _ResetAnimState()`

- `Void EventOnFogClicked()`

- `Void _OnUnlockableFogClicked(Param)`

- `Void _OnFogUnlockItemNotEnough(Param)`

- `Void _OnFogUnlockStageNotPass(Param, StageData)`

- `Void <>xLuaBaseProxy_OnFogDismiss()`

- `Void <>xLuaBaseProxy_OnStageNotOpen(StageFogInfo)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act12side.UI
public class Act12sideStageFog : StageFogOnMapBase
{
	private List`1 _unlockableItems; // 0x28
	private Text _textUnlockCount; // 0x30
	private Text _textUnlockDesc; // 0x38
	private Image _iconUnlockItem; // 0x40
	private Button _btnUnlock; // 0x48
	private GameObject[] _lockedObjs; // 0x50
	private GameObject[] _unlockObjs; // 0x58
	private UIAnimationLocation _dismissAnim; // 0x60
	private GameObject _panelInfo; // 0x70
	private String m_cachedStageId; // 0x78
	private Param m_cachedParam; // 0x80
	private static DelegateBridge __Hotfix0_RenderView; // 0x0
	private static DelegateBridge __Hotfix0_OnFogDismiss; // 0x8
	private static DelegateBridge __Hotfix0_OnStageNotOpen; // 0x10
	private static DelegateBridge __Hotfix0__FakeRenderViewOnStageNotOpen; // 0x18
	private static DelegateBridge __Hotfix0__RenderViewImpl; // 0x20
	private static DelegateBridge __Hotfix0__ResetAnimState; // 0x28
	private static DelegateBridge __Hotfix0_EventOnFogClicked; // 0x30
	private static DelegateBridge __Hotfix0__OnUnlockableFogClicked; // 0x38
	private static DelegateBridge __Hotfix0__OnFogUnlockItemNotEnough; // 0x40
	private static DelegateBridge __Hotfix0__OnFogUnlockStageNotPass; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x345bebc VA: 0x7595a73ebc
	public override Void RenderView(Param renderParam) { }
	// RVA: 0x345c330 VA: 0x7595a74330
	protected override Void OnFogDismiss() { }
	// RVA: 0x345c3dc VA: 0x7595a743dc
	protected override Void OnStageNotOpen(StageFogInfo fogInfo) { }
	// RVA: 0x345c46c VA: 0x7595a7446c
	private Void _FakeRenderViewOnStageNotOpen(StageFogInfo fogInfo) { }
	// RVA: 0x345bf60 VA: 0x7595a73f60
	private Void _RenderViewImpl(Param renderParam) { }
	// RVA: 0x345c53c VA: 0x7595a7453c
	private Void _ResetAnimState() { }
	// RVA: 0x345c5b4 VA: 0x7595a745b4
	public Void EventOnFogClicked() { }
	// RVA: 0x345c770 VA: 0x7595a74770
	private Void _OnUnlockableFogClicked(Param param) { }
	// RVA: 0x345c834 VA: 0x7595a74834
	private Void _OnFogUnlockItemNotEnough(Param param) { }
	// RVA: 0x345c95c VA: 0x7595a7495c
	private Void _OnFogUnlockStageNotPass(Param param, StageData prevStage) { }
	// RVA: 0x345ca34 VA: 0x7595a74a34
	public Void .ctor() { }
	// RVA: 0x345caa4 VA: 0x7595a74aa4
	private Void <>xLuaBaseProxy_OnFogDismiss() { }
	// RVA: 0x345caac VA: 0x7595a74aac
	private Void <>xLuaBaseProxy_OnStageNotOpen(StageFogInfo P0) { }
}
```