# Act13sideStageFog

**Namespace:** `Torappu.Activity.Act13Side.UI`


## Fields

- `Text _textUnlockCount`

- `Text _textUnlockDesc`

- `Image _iconUnlockItem`

- `CanvasGroup _fogCanvasGroup`

- `String m_cachedStageId`

- `Param m_cachedParam`


## Methods

- `Void _RenderViewImpl(Param)`

- `Void EventOnFogClicked()`

- `Void _OnUnlockableFogClicked(Param)`

- `Void _OnFogUnlockItemNotEnough(Param)`

- `Void <OnFogDismiss>b__9_0()`

- `Void <>xLuaBaseProxy_OnFogDismiss()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act13Side.UI
public class Act13sideStageFog : StageFogOnMapBase
{
	private GameObject[] _lockedObjs; // 0x28
	private GameObject[] _unlockObjs; // 0x30
	private Text _textUnlockCount; // 0x38
	private Text _textUnlockDesc; // 0x40
	private Image _iconUnlockItem; // 0x48
	private CanvasGroup _fogCanvasGroup; // 0x50
	private String m_cachedStageId; // 0x58
	private Param m_cachedParam; // 0x60
	private static DelegateBridge __Hotfix0_RenderView; // 0x0
	private static DelegateBridge __Hotfix0_OnFogDismiss; // 0x8
	private static DelegateBridge __Hotfix0__RenderViewImpl; // 0x10
	private static DelegateBridge __Hotfix0_EventOnFogClicked; // 0x18
	private static DelegateBridge __Hotfix0__OnUnlockableFogClicked; // 0x20
	private static DelegateBridge __Hotfix0__OnFogUnlockItemNotEnough; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x3445e6c VA: 0x7595a5de6c
	public override Void RenderView(Param renderParam) { }
	// RVA: 0x34461a8 VA: 0x7595a5e1a8
	protected override Void OnFogDismiss() { }
	// RVA: 0x3445f10 VA: 0x7595a5df10
	private Void _RenderViewImpl(Param renderParam) { }
	// RVA: 0x34462d0 VA: 0x7595a5e2d0
	public Void EventOnFogClicked() { }
	// RVA: 0x34464ec VA: 0x7595a5e4ec
	private Void _OnUnlockableFogClicked(Param param) { }
	// RVA: 0x34465b0 VA: 0x7595a5e5b0
	private Void _OnFogUnlockItemNotEnough(Param param) { }
	// RVA: 0x34466d8 VA: 0x7595a5e6d8
	public Void .ctor() { }
	// RVA: 0x3446748 VA: 0x7595a5e748
	private Void <OnFogDismiss>b__9_0() { }
	// RVA: 0x3446764 VA: 0x7595a5e764
	private Void <>xLuaBaseProxy_OnFogDismiss() { }
}
```