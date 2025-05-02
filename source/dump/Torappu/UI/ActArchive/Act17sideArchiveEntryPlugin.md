# Act17sideArchiveEntryPlugin

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `RectTransform _btnLandmark`

- `RectTransform _btnLog`

- `RectTransform _btnMusic`

- `RectTransform _btnPic`

- `CanvasGroup _canvasGroupLandmark`

- `CanvasGroup _canvasGroupLog`

- `CanvasGroup _canvasGroupMusic`

- `CanvasGroup _canvasGroupPic`

- `Boolean m_entryAnimPlayed`

- `Tween m_cachedTween`


## Methods

- `Tween GenerateEnterTween()`

- `Tween GenerateLoopTween()`

- `Void ResetBtnStatus(Boolean)`

- `Void <OnEnter>b__10_0()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnExit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class Act17sideArchiveEntryPlugin : ArchiveActivityEntryPlugin
{
	private RectTransform _btnLandmark; // 0x18
	private RectTransform _btnLog; // 0x20
	private RectTransform _btnMusic; // 0x28
	private RectTransform _btnPic; // 0x30
	private CanvasGroup _canvasGroupLandmark; // 0x38
	private CanvasGroup _canvasGroupLog; // 0x40
	private CanvasGroup _canvasGroupMusic; // 0x48
	private CanvasGroup _canvasGroupPic; // 0x50
	private Boolean m_entryAnimPlayed; // 0x58
	private Tween m_cachedTween; // 0x60
	private static DelegateBridge __Hotfix0_OnEnter; // 0x0
	private static DelegateBridge __Hotfix0_OnExit; // 0x8
	private static DelegateBridge __Hotfix0_GenerateEnterTween; // 0x10
	private static DelegateBridge __Hotfix0_GenerateLoopTween; // 0x18
	private static DelegateBridge __Hotfix0_ResetBtnStatus; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x3004470 VA: 0x759561c470
	public override Void OnEnter() { }
	// RVA: 0x300505c VA: 0x759561d05c
	public override Void OnExit() { }
	// RVA: 0x30048b4 VA: 0x759561c8b4
	public Tween GenerateEnterTween() { }
	// RVA: 0x3004bfc VA: 0x759561cbfc
	public Tween GenerateLoopTween() { }
	// RVA: 0x30045d0 VA: 0x759561c5d0
	public Void ResetBtnStatus(Boolean isShow) { }
	// RVA: 0x30050fc VA: 0x759561d0fc
	public Void .ctor() { }
	// RVA: 0x300516c VA: 0x759561d16c
	private Void <OnEnter>b__10_0() { }
	// RVA: 0x30051cc VA: 0x759561d1cc
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x30051d4 VA: 0x759561d1d4
	private Void <>xLuaBaseProxy_OnExit() { }
}
```