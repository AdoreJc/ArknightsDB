# AVGCharacterslotPanel

**Namespace:** `Torappu.AVG`


## Fields

- `AVGCharacterSlot _middleSlot`

- `AVGCharacterSlot _leftSlot`

- `AVGCharacterSlot _rightSlot`

- `Color _focusColor`

- `Color _unfocusColor`

- `Boolean m_focusLeft`

- `Boolean m_focusRight`

- `Boolean m_focusMiddle`

- `PostDisplayHandler m_ghostLeft`

- `PostDisplayHandler m_ghostRight`

- `PostDisplayHandler m_ghostMiddle`

- `Sequence m_leftSeq`

- `Sequence m_rightSeq`

- `Sequence m_middleSeq`

- `Boolean m_leftSeqPlayed`

- `Boolean m_rightSeqPlayed`

- `Boolean m_middleSeqPlayed`


## Methods

- `AbstractResRefCollecter DontInvoke_PlzImplInternalResRefCollector()`

- `Boolean _ExecuteCharslotMask(Command)`

- `Boolean _ExecuteCharslot(Command)`

- `Boolean _CleanSlotsWithTween(Single, Boolean)`

- `Void _UpdateSeqWithTween(ref, Tween, Single)`

- `Sequence _DoCleanSlot(String, Single)`

- `Void _SetSeqPlayed(String)`

- `Vector2 _GenPos(String)`

- `Void _ProcessFocusArray(String[])`

- `Void _UpdateSeqWithParam(ref, TweenerOptions)`

- `Tween _GenSlotActionTw(AVGCharacterSlot, TweenerOptions)`

- `Tween _GenCharslotJump(AVGCharacterSlot, TweenerOptions)`

- `Tween _GenCharslotZoom(AVGCharacterSlot, TweenerOptions)`

- `Tween _GenCharslotShake(AVGCharacterSlot, TweenerOptions)`

- `Tween _GenCharslotMove(AVGCharacterSlot, TweenerOptions)`

- `Tween _GenCharslotShakemove(AVGCharacterSlot, TweenerOptions)`

- `Color _GetSlotColorWithFocus(String)`

- `Boolean _GetSlotFocusStatus(String)`

- `Void _ResetSlotFocusStatus(String)`

- `Void _ProcessCharFocus()`

- `AVGCharacterSlot _GetSlotWithName(String)`

- `Sequence _GetCachedSlotSeq(String)`

- `Void _ClearSeq()`

- `Void _InitCamEffectBind()`

- `Boolean NeedSkipAnimation(Single)`

- `Single CalculateFadetime(Single)`

- `Void <_ExecuteCharslotMask>b__27_0()`

- `Void <_CleanSlotsWithTween>b__29_0()`

- `Void <_CleanSlotsWithTween>b__29_1()`

- `Void <_CleanSlotsWithTween>b__29_2()`

- `Void <>xLuaBaseProxy_OnReset()`

- `Void <>xLuaBaseProxy_OnStoryBegin(Story)`

- `Void <>xLuaBaseProxy_OnStoryEnd(Story)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.AVG
public class AVGCharacterslotPanel : ExecutorComponent, IContainsResRefs, IFadeTimeRatio
{
	private AVGCharacterSlot _middleSlot; // 0x50
	private AVGCharacterSlot _leftSlot; // 0x58
	private AVGCharacterSlot _rightSlot; // 0x60
	private Color _focusColor; // 0x68
	private Color _unfocusColor; // 0x78
	private const String SLOT_LEFT; // 0x0
	private const String SLOT_RIGHT; // 0x0
	private const String SLOT_MIDDLE; // 0x0
	private const String SLOT_LEFT_SHORT; // 0x0
	private const String SLOT_RIGHT_SHORT; // 0x0
	private const String SLOT_MIDDLE_SHORT; // 0x0
	private const String SLOT_ALL; // 0x0
	private const String SLOT_NONE; // 0x0
	private const Single ALPHA_ZERO; // 0x0
	private const Single ALPHA_ONE; // 0x0
	private const Single ALPHA_DEFAULT; // 0x0
	private const String EMPTY_CHAR; // 0x0
	private Boolean m_focusLeft; // 0x88
	private Boolean m_focusRight; // 0x89
	private Boolean m_focusMiddle; // 0x8a
	private PostDisplayHandler m_ghostLeft; // 0x90
	private PostDisplayHandler m_ghostRight; // 0x98
	private PostDisplayHandler m_ghostMiddle; // 0xa0
	private Sequence m_leftSeq; // 0xa8
	private Sequence m_rightSeq; // 0xb0
	private Sequence m_middleSeq; // 0xb8
	private Boolean m_leftSeqPlayed; // 0xc0
	private Boolean m_rightSeqPlayed; // 0xc1
	private Boolean m_middleSeqPlayed; // 0xc2
	private static DelegateBridge __Hotfix0_DontInvoke_PlzImplInternalResRefCollector; // 0x0
	private static DelegateBridge __Hotfix0_GetExecutors; // 0x8
	private static DelegateBridge __Hotfix0__ExecuteCharslotMask; // 0x10
	private static DelegateBridge __Hotfix0__ExecuteCharslot; // 0x18
	private static DelegateBridge __Hotfix0__CleanSlotsWithTween; // 0x20
	private static DelegateBridge __Hotfix0__UpdateSeqWithTween; // 0x28
	private static DelegateBridge __Hotfix0__DoCleanSlot; // 0x30
	private static DelegateBridge __Hotfix0__SetSeqPlayed; // 0x38
	private static DelegateBridge __Hotfix0__GenPos; // 0x40
	private static DelegateBridge __Hotfix0__ProcessFocusArray; // 0x48
	private static DelegateBridge __Hotfix0__UpdateSeqWithParam; // 0x50
	private static DelegateBridge __Hotfix0__GenSlotActionTw; // 0x58
	private static DelegateBridge __Hotfix0__GenCharslotJump; // 0x60
	private static DelegateBridge __Hotfix0__GenCharslotZoom; // 0x68
	private static DelegateBridge __Hotfix0__GenCharslotShake; // 0x70
	private static DelegateBridge __Hotfix0__GenCharslotMove; // 0x78
	private static DelegateBridge __Hotfix0__GenCharslotShakemove; // 0x80
	private static DelegateBridge __Hotfix0__GetSlotColorWithFocus; // 0x88
	private static DelegateBridge __Hotfix0__GetSlotFocusStatus; // 0x90
	private static DelegateBridge __Hotfix0__ResetSlotFocusStatus; // 0x98
	private static DelegateBridge __Hotfix0__ProcessCharFocus; // 0xa0
	private static DelegateBridge __Hotfix0__GetSlotWithName; // 0xa8
	private static DelegateBridge __Hotfix0__GetCachedSlotSeq; // 0xb0
	private static DelegateBridge __Hotfix0__ClearSeq; // 0xb8
	private static DelegateBridge __Hotfix0_OnReset; // 0xc0
	private static DelegateBridge __Hotfix0_ForceCommandEnd; // 0xc8
	private static DelegateBridge __Hotfix0_OnStoryBegin; // 0xd0
	private static DelegateBridge __Hotfix0__InitCamEffectBind; // 0xd8
	private static DelegateBridge __Hotfix0_OnStoryEnd; // 0xe0
	private static DelegateBridge __Hotfix0_NeedSkipAnimation; // 0xe8
	private static DelegateBridge __Hotfix0_CalculateFadetime; // 0xf0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xf8


	// RVA: 0x3e6ab54 VA: 0x7596482b54
	public AbstractResRefCollecter DontInvoke_PlzImplInternalResRefCollector() { }
	// RVA: 0x3e6ac74 VA: 0x7596482c74
	public override Dictionary`2 GetExecutors() { }
	// RVA: 0x3e6ae18 VA: 0x7596482e18
	private Boolean _ExecuteCharslotMask(Command command) { }
	// RVA: 0x3e6b3c8 VA: 0x75964833c8
	private Boolean _ExecuteCharslot(Command command) { }
	// RVA: 0x3e6c24c VA: 0x759648424c
	private Boolean _CleanSlotsWithTween(Single duartion, Boolean isBlock) { }
	// RVA: 0x3e6cc80 VA: 0x7596484c80
	private Void _UpdateSeqWithTween(ref Sequence curSeq, Tween tw, Single delay) { }
	// RVA: 0x3e6cae8 VA: 0x7596484ae8
	private Sequence _DoCleanSlot(String slotType, Single duration) { }
	// RVA: 0x3e6cd48 VA: 0x7596484d48
	private Void _SetSeqPlayed(String slotType) { }
	// RVA: 0x3e6c028 VA: 0x7596484028
	private Vector2 _GenPos(String posRaw) { }
	// RVA: 0x3e6ced0 VA: 0x7596484ed0
	private Void _ProcessFocusArray(String[] focusArray) { }
	// RVA: 0x3e6c750 VA: 0x7596484750
	private Void _UpdateSeqWithParam(ref Sequence cacheSeq, TweenerOptions options) { }
	// RVA: 0x3e6d3e0 VA: 0x75964853e0
	private Tween _GenSlotActionTw(AVGCharacterSlot slot, TweenerOptions options) { }
	// RVA: 0x3e6d67c VA: 0x759648567c
	private Tween _GenCharslotJump(AVGCharacterSlot slot, TweenerOptions options) { }
	// RVA: 0x3e6d74c VA: 0x759648574c
	private Tween _GenCharslotZoom(AVGCharacterSlot slot, TweenerOptions options) { }
	// RVA: 0x3e6d7ec VA: 0x75964857ec
	private Tween _GenCharslotShake(AVGCharacterSlot slot, TweenerOptions options) { }
	// RVA: 0x3e6d5dc VA: 0x75964855dc
	private Tween _GenCharslotMove(AVGCharacterSlot slot, TweenerOptions options) { }
	// RVA: 0x3e6d8b0 VA: 0x75964858b0
	private Tween _GenCharslotShakemove(AVGCharacterSlot slot, TweenerOptions options) { }
	// RVA: 0x3e6d1b0 VA: 0x75964851b0
	private Color _GetSlotColorWithFocus(String slot) { }
	// RVA: 0x3e6d254 VA: 0x7596485254
	private Boolean _GetSlotFocusStatus(String slot) { }
	// RVA: 0x3e6d994 VA: 0x7596485994
	private Void _ResetSlotFocusStatus(String slot) { }
	// RVA: 0x3e6d104 VA: 0x7596485104
	private Void _ProcessCharFocus() { }
	// RVA: 0x3e6b244 VA: 0x7596483244
	private AVGCharacterSlot _GetSlotWithName(String slot) { }
	// RVA: 0x3e6c4c0 VA: 0x75964844c0
	private Sequence _GetCachedSlotSeq(String slotType) { }
	// RVA: 0x3e6db10 VA: 0x7596485b10
	private Void _ClearSeq() { }
	// RVA: 0x3e6dbe4 VA: 0x7596485be4
	public override Void OnReset() { }
	// RVA: 0x3e6dc94 VA: 0x7596485c94
	protected override Void ForceCommandEnd() { }
	// RVA: 0x3e6dcf8 VA: 0x7596485cf8
	public override Void OnStoryBegin(Story story) { }
	// RVA: 0x3e6dd74 VA: 0x7596485d74
	private Void _InitCamEffectBind() { }
	// RVA: 0x3e6ded4 VA: 0x7596485ed4
	public override Void OnStoryEnd(Story story) { }
	// RVA: 0x3e6c1a8 VA: 0x75964841a8
	public Boolean NeedSkipAnimation(Single fadetime) { }
	// RVA: 0x3e6b19c VA: 0x759648319c
	public Single CalculateFadetime(Single initialFadetime) { }
	// RVA: 0x3e6dfa0 VA: 0x7596485fa0
	public Void .ctor() { }
	// RVA: 0x3e6e024 VA: 0x7596486024
	private Void <_ExecuteCharslotMask>b__27_0() { }
	// RVA: 0x3e6e02c VA: 0x759648602c
	private Void <_CleanSlotsWithTween>b__29_0() { }
	// RVA: 0x3e6e074 VA: 0x7596486074
	private Void <_CleanSlotsWithTween>b__29_1() { }
	// RVA: 0x3e6e0bc VA: 0x75964860bc
	private Void <_CleanSlotsWithTween>b__29_2() { }
	// RVA: 0x3e6e110 VA: 0x7596486110
	private Void <>xLuaBaseProxy_OnReset() { }
	// RVA: 0x3e6e118 VA: 0x7596486118
	private Void <>xLuaBaseProxy_OnStoryBegin(Story P0) { }
	// RVA: 0x3e6e120 VA: 0x7596486120
	private Void <>xLuaBaseProxy_OnStoryEnd(Story P0) { }
}
```