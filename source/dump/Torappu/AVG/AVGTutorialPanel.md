# AVGTutorialPanel

**Namespace:** `Torappu.AVG`


## Fields

- `AVGFakeButton _fakeBtn`

- `Graphic _fakeGraphic`

- `AVGTutorialFocus _focus`

- `AVGTutorialPointer _pointer`

- `AVGTutorialDialog _dialog`

- `Graphic _inputBlocker`

- `Graphic _btnClickBlocker`

- `Image _inputBlockerBackground`

- `Single _highlightDefaultProtectTime`

- `String m_waitForSignal`

- `String m_abortForSignal`

- `Boolean m_waitForHighlightClick`

- `Boolean m_waitForDialogClick`

- `Boolean m_waitForDragAnimationClick`

- `Single m_highlightProtectTime`

- `IAVGTutorialPanelPlugin m_plugin`


## Methods

- `Boolean _ExecuteTutorial(Command)`

- `Void CommonFallback()`

- `Void _ReceiveTutorialSignal(Command)`

- `Void _RearrangePartialBlockers(Rect)`

- `Void _HidePartialBlockers()`

- `Boolean _ExecuteInputBlocker(Command)`

- `Boolean _IsInputBlockerValidAreaSet(Command, ref)`

- `Void _GetCenterAnchorPos(Command, ref)`

- `Boolean _SetButtonTarget(String, Boolean)`

- `Void _OnHighlightClicked(Object)`

- `Void _DoHighlightClicked()`

- `Void _OnPopupDialogClicked(Object)`

- `Void _DoPopupDialogClicked()`

- `Void _OnDragAnimationClicked(Object)`

- `Void _OnFakeButtonClicked()`

- `Void _Hide()`

- `Void Awake()`

- `Void Update()`

- `Single CalculateFadetime(Single)`

- `Boolean NeedSkipAnimation(Single)`

- `Boolean RegisterPlugin(IAVGTutorialPanelPlugin)`

- `Void ClearPlugin()`

- `Void <>xLuaBaseProxy_OnReset()`

- `Void <>xLuaBaseProxy_OnStoryEnd(Story)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.AVG
public class AVGTutorialPanel : ExecutorComponent, IFadeTimeRatio
{
	private const AnchorType DEFAULT_ANCHOR; // 0x0
	private AVGFakeButton _fakeBtn; // 0x50
	private Graphic _fakeGraphic; // 0x58
	private AVGTutorialFocus _focus; // 0x60
	private AVGTutorialPointer _pointer; // 0x68
	private AVGTutorialDialog _dialog; // 0x70
	private Graphic _inputBlocker; // 0x78
	private Graphic _btnClickBlocker; // 0x80
	private Graphic[] _inputPartialBlockers; // 0x88
	private Image _inputBlockerBackground; // 0x90
	private Single _highlightDefaultProtectTime; // 0x98
	private String m_waitForSignal; // 0xa0
	private String m_abortForSignal; // 0xa8
	private Boolean m_waitForHighlightClick; // 0xb0
	private Boolean m_waitForDialogClick; // 0xb1
	private Boolean m_waitForDragAnimationClick; // 0xb2
	private Single m_highlightProtectTime; // 0xb4
	private IAVGTutorialPanelPlugin m_plugin; // 0xb8
	private static DelegateBridge __Hotfix0_GetExecutors; // 0x0
	private static DelegateBridge __Hotfix0_GetSignalReceivers; // 0x8
	private static DelegateBridge __Hotfix0_OnReset; // 0x10
	private static DelegateBridge __Hotfix0_OnStoryEnd; // 0x18
	private static DelegateBridge __Hotfix0__ExecuteTutorial; // 0x20
	private static DelegateBridge __Hotfix0_CommonFallback; // 0x28
	private static DelegateBridge __Hotfix0__ReceiveTutorialSignal; // 0x30
	private static DelegateBridge __Hotfix0__RearrangePartialBlockers; // 0x38
	private static DelegateBridge __Hotfix0__HidePartialBlockers; // 0x40
	private static DelegateBridge __Hotfix0__ExecuteInputBlocker; // 0x48
	private static DelegateBridge __Hotfix0__IsInputBlockerValidAreaSet; // 0x50
	private static DelegateBridge __Hotfix0__GetCenterAnchorPos; // 0x58
	private static DelegateBridge __Hotfix0__SetButtonTarget; // 0x60
	private static DelegateBridge __Hotfix0__OnHighlightClicked; // 0x68
	private static DelegateBridge __Hotfix0__DoHighlightClicked; // 0x70
	private static DelegateBridge __Hotfix0__OnPopupDialogClicked; // 0x78
	private static DelegateBridge __Hotfix0__DoPopupDialogClicked; // 0x80
	private static DelegateBridge __Hotfix0__OnDragAnimationClicked; // 0x88
	private static DelegateBridge __Hotfix0__AlignRectTransform; // 0x90
	private static DelegateBridge __Hotfix0__OnFakeButtonClicked; // 0x98
	private static DelegateBridge __Hotfix0__Hide; // 0xa0
	private static DelegateBridge __Hotfix0_ResetAnchor; // 0xa8
	private static DelegateBridge __Hotfix0_ForceCommandEnd; // 0xb0
	private static DelegateBridge __Hotfix0_Awake; // 0xb8
	private static DelegateBridge __Hotfix0_Update; // 0xc0
	private static DelegateBridge __Hotfix0_CalculateFadetime; // 0xc8
	private static DelegateBridge __Hotfix0_NeedSkipAnimation; // 0xd0
	private static DelegateBridge __Hotfix0_RegisterPlugin; // 0xd8
	private static DelegateBridge __Hotfix0_ClearPlugin; // 0xe0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xe8


	// RVA: 0x3e75c84 VA: 0x759648dc84
	public override Dictionary`2 GetExecutors() { }
	// RVA: 0x3e75e70 VA: 0x759648de70
	public override Dictionary`2 GetSignalReceivers() { }
	// RVA: 0x3e75fac VA: 0x759648dfac
	public override Void OnReset() { }
	// RVA: 0x3e76340 VA: 0x759648e340
	public override Void OnStoryEnd(Story story) { }
	// RVA: 0x3e7644c VA: 0x759648e44c
	private Boolean _ExecuteTutorial(Command command) { }
	// RVA: 0x3e779b0 VA: 0x759648f9b0
	public Void CommonFallback() { }
	// RVA: 0x3e77ad0 VA: 0x759648fad0
	private Void _ReceiveTutorialSignal(Command command) { }
	// RVA: 0x3e77c4c VA: 0x759648fc4c
	private Void _RearrangePartialBlockers(Rect validArea) { }
	// RVA: 0x3e76288 VA: 0x759648e288
	private Void _HidePartialBlockers() { }
	// RVA: 0x3e77f5c VA: 0x759648ff5c
	private Boolean _ExecuteInputBlocker(Command command) { }
	// RVA: 0x3e7844c VA: 0x759649044c
	private Boolean _IsInputBlockerValidAreaSet(Command command, ref Vector2 validXY) { }
	// RVA: 0x3e7776c VA: 0x759648f76c
	private Void _GetCenterAnchorPos(Command command, ref Vector2 validXY) { }
	// RVA: 0x3e77220 VA: 0x759648f220
	private Boolean _SetButtonTarget(String targetName, Boolean searchBtnInChildren) { }
	// RVA: 0x3e78b98 VA: 0x7596490b98
	private Void _OnHighlightClicked(Object arg) { }
	// RVA: 0x3e78c94 VA: 0x7596490c94
	private Void _DoHighlightClicked() { }
	// RVA: 0x3e78e40 VA: 0x7596490e40
	private Void _OnPopupDialogClicked(Object arg) { }
	// RVA: 0x3e78f3c VA: 0x7596490f3c
	private Void _DoPopupDialogClicked() { }
	// RVA: 0x3e7906c VA: 0x759649106c
	private Void _OnDragAnimationClicked(Object arg) { }
	// RVA: 0x3e786f0 VA: 0x75964906f0
	private static Void _AlignRectTransform(Graphic currentGraphic, Graphic targetGraphic) { }
	// RVA: 0x3e78db0 VA: 0x7596490db0
	private Void _OnFakeButtonClicked() { }
	// RVA: 0x3e77a24 VA: 0x759648fa24
	private Void _Hide() { }
	// RVA: 0x3e79200 VA: 0x7596491200
	public static Void ResetAnchor(RectTransform transform, AnchorType anchor) { }
	// RVA: 0x3e79330 VA: 0x7596491330
	protected override Void ForceCommandEnd() { }
	// RVA: 0x3e79394 VA: 0x7596491394
	private Void Awake() { }
	// RVA: 0x3e79458 VA: 0x7596491458
	private Void Update() { }
	// RVA: 0x3e783a4 VA: 0x75964903a4
	public Single CalculateFadetime(Single initialFadetime) { }
	// RVA: 0x3e794e4 VA: 0x75964914e4
	public Boolean NeedSkipAnimation(Single fadetime) { }
	// RVA: 0x3e79588 VA: 0x7596491588
	public Boolean RegisterPlugin(IAVGTutorialPanelPlugin plugin) { }
	// RVA: 0x3e79668 VA: 0x7596491668
	public Void ClearPlugin() { }
	// RVA: 0x3e796d8 VA: 0x75964916d8
	public Void .ctor() { }
	// RVA: 0x3e79750 VA: 0x7596491750
	private Dictionary`2 <>xLuaBaseProxy_GetSignalReceivers() { }
	// RVA: 0x3e79758 VA: 0x7596491758
	private Void <>xLuaBaseProxy_OnReset() { }
	// RVA: 0x3e79760 VA: 0x7596491760
	private Void <>xLuaBaseProxy_OnStoryEnd(Story P0) { }
}
```