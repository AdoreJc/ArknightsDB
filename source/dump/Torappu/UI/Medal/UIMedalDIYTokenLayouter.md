# UIMedalDIYTokenLayouter

**Namespace:** `Torappu.UI.Medal`


## Fields

- `RectTransform _tokenContainer`

- `RectTransform _frameContainer`

- `RectTransform _validPosContainer`

- `UIMedalDIYTokenView _tokenPrefab`

- `UIMedalDIYFrame m_frame`

- `IMedalDIYContext m_context`


## Properties

- `RectTransform tokenContainer`


## Methods

- `Void Init(String, IMedalDIYContext)`

- `Void UpdateStatus(MedalDIYViewModel, Boolean, ref)`

- `UIMedalDIYTokenView GetTokenOrCreate(DIYMedalModel)`

- `Void SetHexPosition(RectTransform, HexPoint, Boolean)`

- `UIMedalDIYFrame GetFrame()`

- `RectTransform get_tokenContainer()`

- `Void ClearEvents()`

- `Void _ClearAllTokens()`

- `Void _RemoveToken(UIMedalDIYTokenView, Boolean)`

- `UIMedalDIYTokenView _CreateToken(DIYMedalModel)`

- `Void _TweenViewTo(RectTransform, Vector2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Medal
public class UIMedalDIYTokenLayouter : MonoBehaviour, IHotfixable
{
	private const Single TWEEN_DUR; // 0x0
	private RectTransform _tokenContainer; // 0x18
	private RectTransform _frameContainer; // 0x20
	private RectTransform _validPosContainer; // 0x28
	private UIMedalDIYTokenView _tokenPrefab; // 0x30
	private Dictionary`2 m_tokens; // 0x38
	private Dictionary`2 m_medalMoveTweens; // 0x40
	private UIMedalDIYFrame m_frame; // 0x48
	private IMedalDIYContext m_context; // 0x50
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_UpdateStatus; // 0x8
	private static DelegateBridge __Hotfix0_GetTokenOrCreate; // 0x10
	private static DelegateBridge __Hotfix0_SetHexPosition; // 0x18
	private static DelegateBridge __Hotfix0_GetFrame; // 0x20
	private static DelegateBridge __Hotfix0_get_tokenContainer; // 0x28
	private static DelegateBridge __Hotfix0_ClearEvents; // 0x30
	private static DelegateBridge __Hotfix0__ClearAllTokens; // 0x38
	private static DelegateBridge __Hotfix0__RemoveToken; // 0x40
	private static DelegateBridge __Hotfix0__CreateToken; // 0x48
	private static DelegateBridge __Hotfix0__TweenViewTo; // 0x50
	private static DelegateBridge __Hotfix0__PlayAudioWhenViewTweened; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	public RectTransform tokenContainer { get; }

	// RVA: 0x27699dc VA: 0x7594d819dc
	public Void Init(String frameId, IMedalDIYContext context) { }
	// RVA: 0x276bd58 VA: 0x7594d83d58
	public Void UpdateStatus(MedalDIYViewModel viewModel, Boolean immediately, ref ListDict`2 removedTokens) { }
	// RVA: 0x276a974 VA: 0x7594d82974
	public UIMedalDIYTokenView GetTokenOrCreate(DIYMedalModel model) { }
	// RVA: 0x276b8a8 VA: 0x7594d838a8
	public Void SetHexPosition(RectTransform rectTrans, HexPoint hexPoint, Boolean immediately) { }
	// RVA: 0x276aea0 VA: 0x7594d82ea0
	public UIMedalDIYFrame GetFrame() { }
	// RVA: 0x276aaac VA: 0x7594d82aac
	public RectTransform get_tokenContainer() { }
	// RVA: 0x276aca4 VA: 0x7594d82ca4
	public Void ClearEvents() { }
	// RVA: 0x276c570 VA: 0x7594d84570
	private Void _ClearAllTokens() { }
	// RVA: 0x276c6f8 VA: 0x7594d846f8
	private Void _RemoveToken(UIMedalDIYTokenView token, Boolean immediately) { }
	// RVA: 0x276c8d4 VA: 0x7594d848d4
	private UIMedalDIYTokenView _CreateToken(DIYMedalModel model) { }
	// RVA: 0x276c9cc VA: 0x7594d849cc
	private Void _TweenViewTo(RectTransform rectTrans, Vector2 targetPos) { }
	// RVA: 0x276cd5c VA: 0x7594d84d5c
	private static Void _PlayAudioWhenViewTweened(RectTransform rectTrans) { }
	// RVA: 0x276ce9c VA: 0x7594d84e9c
	public Void .ctor() { }
}
```