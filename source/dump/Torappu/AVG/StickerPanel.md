# StickerPanel

**Namespace:** `Torappu.AVG`


## Fields

- `RectTransform _stickerContainer`

- `AVGStickerTextView _stickerPrefab`

- `AVGTimerView _timerStickerPrefab`

- `AVGStickerTextView m_currentSticker`

- `AVGTimerView m_currentTimer`

- `Boolean m_inited`


## Methods

- `Void _InitIfNot()`

- `Boolean _ExecuteSticker(Command)`

- `StickerParam _GenParam(Command, String)`

- `AVGStickerTextView _GenSticker(String)`

- `Boolean _ExcuteClear(Command)`

- `Void _AppendStickerText(String, AVGStickerTextView)`

- `Void _HideSticker(String, AVGStickerTextView, Single)`

- `Void _RecycleStickers()`

- `Void _OnStickerTypeEnd(Int32)`

- `Void _SetTypeWriterDelay(Object)`

- `Boolean _ExcuteTimerSticker(Command)`

- `Boolean _ExcuteTimerClier(Command)`

- `Void <>xLuaBaseProxy_OnStoryBegin(Story)`

- `Void <>xLuaBaseProxy_OnReset()`

- `Void <>xLuaBaseProxy_OnFinish()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.AVG
public class StickerPanel : ExecutorComponent
{
	private const Single SCREEN_WIDTH; // 0x0
	private const Single SCREEN_HEIGHT; // 0x0
	private const Int32 STICKER_MAX_NUM; // 0x0
	private const Single DEFAULT_FADE_DURATION; // 0x0
	private RectTransform _stickerContainer; // 0x50
	private AVGStickerTextView _stickerPrefab; // 0x58
	private AVGTimerView _timerStickerPrefab; // 0x60
	private AVGStickerTextView m_currentSticker; // 0x68
	private Dictionary`2 m_stickerDict; // 0x70
	private List`1 m_recyclePool; // 0x78
	private AVGTimerView m_currentTimer; // 0x80
	private Boolean m_inited; // 0x88
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_GetExecutors; // 0x8
	private static DelegateBridge __Hotfix0_OnStoryBegin; // 0x10
	private static DelegateBridge __Hotfix0_OnReset; // 0x18
	private static DelegateBridge __Hotfix0_ForceCommandEnd; // 0x20
	private static DelegateBridge __Hotfix0_OnFinish; // 0x28
	private static DelegateBridge __Hotfix0__ExecuteSticker; // 0x30
	private static DelegateBridge __Hotfix0__GenParam; // 0x38
	private static DelegateBridge __Hotfix0__GenSticker; // 0x40
	private static DelegateBridge __Hotfix0__ExcuteClear; // 0x48
	private static DelegateBridge __Hotfix0__OnClicked; // 0x50
	private static DelegateBridge __Hotfix0__AppendStickerText; // 0x58
	private static DelegateBridge __Hotfix0__HideSticker; // 0x60
	private static DelegateBridge __Hotfix0__RecycleStickers; // 0x68
	private static DelegateBridge __Hotfix0__OnStickerTypeEnd; // 0x70
	private static DelegateBridge __Hotfix0__SetTypeWriterDelay; // 0x78
	private static DelegateBridge __Hotfix0__ExcuteTimerSticker; // 0x80
	private static DelegateBridge __Hotfix0__ExcuteTimerClier; // 0x88
	private static DelegateBridge _c__Hotfix0_ctor; // 0x90


	// RVA: 0x3e8dcb4 VA: 0x75964a5cb4
	private Void _InitIfNot() { }
	// RVA: 0x3e8dde4 VA: 0x75964a5de4
	public override Dictionary`2 GetExecutors() { }
	// RVA: 0x3e8e040 VA: 0x75964a6040
	public override Void OnStoryBegin(Story story) { }
	// RVA: 0x3e8e25c VA: 0x75964a625c
	public override Void OnReset() { }
	// RVA: 0x3e8e6cc VA: 0x75964a66cc
	protected override Void ForceCommandEnd() { }
	// RVA: 0x3e8e788 VA: 0x75964a6788
	protected override Void OnFinish() { }
	// RVA: 0x3e8e8c8 VA: 0x75964a68c8
	protected Boolean _ExecuteSticker(Command command) { }
	// RVA: 0x3e8f1d8 VA: 0x75964a71d8
	private StickerParam _GenParam(Command command, String textContent) { }
	// RVA: 0x3e8f688 VA: 0x75964a7688
	private AVGStickerTextView _GenSticker(String stickerId) { }
	// RVA: 0x3e8f8d4 VA: 0x75964a78d4
	protected Boolean _ExcuteClear(Command command) { }
	// RVA: 0x3e8fa74 VA: 0x75964a7a74
	protected virtual Void _OnClicked(Object arg) { }
	// RVA: 0x3e8f0fc VA: 0x75964a70fc
	private Void _AppendStickerText(String text, AVGStickerTextView stickerView) { }
	// RVA: 0x3e8ef98 VA: 0x75964a6f98
	private Void _HideSticker(String stickerId, AVGStickerTextView stickerView, Single duration) { }
	// RVA: 0x3e8e3dc VA: 0x75964a63dc
	private Void _RecycleStickers() { }
	// RVA: 0x3e8fbc4 VA: 0x75964a7bc4
	private Void _OnStickerTypeEnd(Int32 msgLenth) { }
	// RVA: 0x3e8e170 VA: 0x75964a6170
	private Void _SetTypeWriterDelay(Object arg) { }
	// RVA: 0x3e8fc68 VA: 0x75964a7c68
	protected Boolean _ExcuteTimerSticker(Command command) { }
	// RVA: 0x3e900f0 VA: 0x75964a80f0
	protected Boolean _ExcuteTimerClier(Command command) { }
	// RVA: 0x3e90264 VA: 0x75964a8264
	public Void .ctor() { }
	// RVA: 0x3e902d4 VA: 0x75964a82d4
	private Void <>xLuaBaseProxy_OnStoryBegin(Story P0) { }
	// RVA: 0x3e902dc VA: 0x75964a82dc
	private Void <>xLuaBaseProxy_OnReset() { }
	// RVA: 0x3e902e4 VA: 0x75964a82e4
	private Void <>xLuaBaseProxy_OnFinish() { }
}
```