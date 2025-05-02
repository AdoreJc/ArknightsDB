# StageFogOnMap

**Namespace:** `Torappu.UI.Stage`


## Fields

- `GameObject _zoneFogPanel`

- `GameObject _stageFogPanel`

- `Button _fogBtn`

- `Image _fogBkg`

- `Image _zoneFogBtnBkg`

- `Image _zoneFogIcon`

- `GameObject _zoneFogDecoContainer`

- `Text _zoneFogUnlockItemCount`

- `Text _zoneFogDesc`

- `Text _zoneFogUnlockTip`

- `GameObject _zoneFogUnlockClickTip`

- `Image _stageFogBtnBkg`

- `Image _stageFogUnlockItemIcon`

- `Text _stageFogUnlockText`

- `Sprite _stageLockedBkg`

- `Sprite _stageUnlockableBkg`

- `Sprite _zoneLockedBkg`

- `Sprite _zoneunLockableBkg`

- `Image _decoImage`

- `Animation _fogDismissAnimation`

- `String m_cachedStageId`


## Methods

- `String _GetFogUnlockDesc(FogType)`

- `Void OnEventClicked()`

- `Void <>xLuaBaseProxy_OnFogDismiss()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageFogOnMap : StageFogOnMapBase
{
	private GameObject _zoneFogPanel; // 0x28
	private GameObject _stageFogPanel; // 0x30
	private Button _fogBtn; // 0x38
	private Image _fogBkg; // 0x40
	private Image _zoneFogBtnBkg; // 0x48
	private Image _zoneFogIcon; // 0x50
	private GameObject _zoneFogDecoContainer; // 0x58
	private Text _zoneFogUnlockItemCount; // 0x60
	private Text _zoneFogDesc; // 0x68
	private Text _zoneFogUnlockTip; // 0x70
	private GameObject _zoneFogUnlockClickTip; // 0x78
	private Image _stageFogBtnBkg; // 0x80
	private Image _stageFogUnlockItemIcon; // 0x88
	private Text _stageFogUnlockText; // 0x90
	private Sprite _stageLockedBkg; // 0x98
	private Sprite _stageUnlockableBkg; // 0xa0
	private Sprite _zoneLockedBkg; // 0xa8
	private Sprite _zoneunLockableBkg; // 0xb0
	private Image _decoImage; // 0xb8
	private Animation _fogDismissAnimation; // 0xc0
	private String m_cachedStageId; // 0xc8
	private static DelegateBridge __Hotfix0_RenderView; // 0x0
	private static DelegateBridge __Hotfix0__GetFogUnlockDesc; // 0x8
	private static DelegateBridge __Hotfix0_OnEventClicked; // 0x10
	private static DelegateBridge __Hotfix0_OnFogDismiss; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2fa4eb0 VA: 0x75955bceb0
	public override Void RenderView(Param renderParam) { }
	// RVA: 0x2fa52a4 VA: 0x75955bd2a4
	private String _GetFogUnlockDesc(FogType fogType) { }
	// RVA: 0x2fa5358 VA: 0x75955bd358
	public Void OnEventClicked() { }
	// RVA: 0x2fa53e0 VA: 0x75955bd3e0
	protected override Void OnFogDismiss() { }
	// RVA: 0x2fa5524 VA: 0x75955bd524
	public Void .ctor() { }
	// RVA: 0x2fa5590 VA: 0x75955bd590
	private Void <>xLuaBaseProxy_OnFogDismiss() { }
}
```