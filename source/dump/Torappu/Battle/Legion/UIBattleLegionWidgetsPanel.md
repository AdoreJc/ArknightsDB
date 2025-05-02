# UIBattleLegionWidgetsPanel

**Namespace:** `Torappu.Battle.Legion`


## Fields

- `GameObject _objBgCanDraw`

- `UIAtlasImage _imgBgCanDraw`

- `GameObject _objDrawIcon`

- `Image _imgDrawIcon`

- `Image _igmDrawDown`

- `GameObject _objDrawBgDownGray`

- `GameObject _objDrawBgDown`

- `RectTransform _transGoldPart`

- `Text _drawNextGoldText`

- `Button _btnDrawCard`

- `RectTransform _transPendingCardTips`

- `Text _remainingCardCountText`

- `RectTransform _transUsedCardTips`

- `Text _usedCardCountText`

- `CanvasGroup _canvasUsedBtn`

- `CanvasGroup _canvasHandCardFullTips`

- `RectTransform _transHandCardFullTips`

- `CanvasGroup _canvasCardFullImg`

- `Text _textAddPrice`

- `GameObject _objGoldFull`

- `GameObject _objGoldNotFull`

- `AnimationWrapper _reshuffleAnim`

- `LegionUIBlastCardEffectHolder _blastEffectHolder`

- `LegionGameMode m_manager`

- `LegionUIPlugin m_plugin`

- `Int32 m_cachedCurrentGoldNum`

- `Int32 m_cachedUsedCardCount`

- `Int32 m_cacaheRemainCardCount`

- `DrawCardTween m_drawCardTween`

- `HandCardFullTipsTween m_handCardFullTipsTween`

- `PendingCardNumChangeTween m_pendingCardNumChangeTween`

- `UsedCardNumChangeTween m_usedCardNumChangeTween`

- `GOLD_DRAW_STATE m_cachedDrawState`

- `Boolean m_hasInited`

- `Boolean m_playingGoldGlowTween`

- `Int32 m_cachedGoldNum`

- `Int32 m_cachedNeedGoldNum`


## Methods

- `Void OnInit(LegionUIPlugin)`

- `Void UpdateGameInfo()`

- `Void OnDrawNextCard()`

- `Void OnShowPendingCard()`

- `Void OnShowUsedCard()`

- `Void _ShowHandCardFullTipsTween()`

- `Void _ShowHandCardFullTipsTween(LegionModeOnCardFullParam)`

- `Void _InitIfNot()`

- `Void _ResetData()`

- `Void _ResetReshuffleBeforePlay()`

- `Void _UpdateReshufflePart()`

- `Void _UpdateUsedCardPart(Int32)`

- `Void _UpdateRemainCardPart(Int32)`

- `Void _UpdateGoldDrawPart(Int32, Int32, Boolean)`

- `GOLD_DRAW_STATE _GetDrawState(Boolean, Boolean)`

- `Void _UpdateGoldDrawPartText(GOLD_DRAW_STATE, Boolean, Int32, Int32)`

- `Void _UpdateGoldDrawPartState(GOLD_DRAW_STATE)`

- `Void _CardFullPutToUsed(LegionModeOnCardFullParam)`

- `Void OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Legion
public class UIBattleLegionWidgetsPanel : MonoBehaviour, IHotfixable
{
	private const String ANIM_RESHUFFLE_CARD_TIPS; // 0x0
	private GameObject _objBgCanDraw; // 0x18
	private UIAtlasImage _imgBgCanDraw; // 0x20
	private GameObject _objDrawIcon; // 0x28
	private Image _imgDrawIcon; // 0x30
	private Image _igmDrawDown; // 0x38
	private GameObject _objDrawBgDownGray; // 0x40
	private GameObject _objDrawBgDown; // 0x48
	private RectTransform _transGoldPart; // 0x50
	private Text _drawNextGoldText; // 0x58
	private Button _btnDrawCard; // 0x60
	private RectTransform _transPendingCardTips; // 0x68
	private Text _remainingCardCountText; // 0x70
	private RectTransform _transUsedCardTips; // 0x78
	private Text _usedCardCountText; // 0x80
	private CanvasGroup _canvasUsedBtn; // 0x88
	private CanvasGroup _canvasHandCardFullTips; // 0x90
	private RectTransform _transHandCardFullTips; // 0x98
	private CanvasGroup _canvasCardFullImg; // 0xa0
	private Text _textAddPrice; // 0xa8
	private GameObject _objGoldFull; // 0xb0
	private GameObject _objGoldNotFull; // 0xb8
	private AnimationWrapper _reshuffleAnim; // 0xc0
	private LegionUIBlastCardEffectHolder _blastEffectHolder; // 0xc8
	private LegionGameMode m_manager; // 0xd0
	private LegionUIPlugin m_plugin; // 0xd8
	private Int32 m_cachedCurrentGoldNum; // 0xe0
	private Int32 m_cachedUsedCardCount; // 0xe4
	private Int32 m_cacaheRemainCardCount; // 0xe8
	private DrawCardTween m_drawCardTween; // 0xf0
	private HandCardFullTipsTween m_handCardFullTipsTween; // 0xf8
	private PendingCardNumChangeTween m_pendingCardNumChangeTween; // 0x100
	private UsedCardNumChangeTween m_usedCardNumChangeTween; // 0x108
	private const String COLOR_TYPE_GOLD_CUR_GLOWING; // 0x0
	private const String COLOR_TYPE_GOLD_CUR_CAN_DRAW; // 0x0
	private const String COLOR_TYPE_GOLD_CUR_FULL; // 0x0
	private const String COLOR_TYPE_GOLD_NEED_CAN_DRAW; // 0x0
	private const String COLOR_TYPE_GOLD_NEED; // 0x0
	private GOLD_DRAW_STATE m_cachedDrawState; // 0x110
	private const Single USED_CARD_EMPTY_ALPHA; // 0x0
	private Boolean m_hasInited; // 0x114
	private Boolean m_playingGoldGlowTween; // 0x115
	private static readonly StringBuilder m_goldTextBuilder; // 0x0
	private Int32 m_cachedGoldNum; // 0x118
	private Int32 m_cachedNeedGoldNum; // 0x11c
	private static DelegateBridge __Hotfix0_OnInit; // 0x8
	private static DelegateBridge __Hotfix0_UpdateGameInfo; // 0x10
	private static DelegateBridge __Hotfix0_OnDrawNextCard; // 0x18
	private static DelegateBridge __Hotfix0_OnShowPendingCard; // 0x20
	private static DelegateBridge __Hotfix0_OnShowUsedCard; // 0x28
	private static DelegateBridge __Hotfix0__ShowHandCardFullTipsTween; // 0x30
	private static DelegateBridge __Hotfix1__ShowHandCardFullTipsTween; // 0x38
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x40
	private static DelegateBridge __Hotfix0__ResetData; // 0x48
	private static DelegateBridge __Hotfix0__ResetReshuffleBeforePlay; // 0x50
	private static DelegateBridge __Hotfix0__UpdateReshufflePart; // 0x58
	private static DelegateBridge __Hotfix0__UpdateUsedCardPart; // 0x60
	private static DelegateBridge __Hotfix0__UpdateRemainCardPart; // 0x68
	private static DelegateBridge __Hotfix0__UpdateGoldDrawPart; // 0x70
	private static DelegateBridge __Hotfix0__GetDrawState; // 0x78
	private static DelegateBridge __Hotfix0__UpdateGoldDrawPartText; // 0x80
	private static DelegateBridge __Hotfix0__UpdateGoldDrawPartState; // 0x88
	private static DelegateBridge __Hotfix0__CardFullPutToUsed; // 0x90
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x98
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa0


	// RVA: 0x1db90d0 VA: 0x75943d10d0
	public Void OnInit(LegionUIPlugin legion) { }
	// RVA: 0x1db9aa4 VA: 0x75943d1aa4
	public Void UpdateGameInfo() { }
	// RVA: 0x1dba20c VA: 0x75943d220c
	public Void OnDrawNextCard() { }
	// RVA: 0x1dba6ec VA: 0x75943d26ec
	public Void OnShowPendingCard() { }
	// RVA: 0x1dba770 VA: 0x75943d2770
	public Void OnShowUsedCard() { }
	// RVA: 0x1dba658 VA: 0x75943d2658
	private Void _ShowHandCardFullTipsTween() { }
	// RVA: 0x1dbac40 VA: 0x75943d2c40
	private Void _ShowHandCardFullTipsTween(LegionModeOnCardFullParam param) { }
	// RVA: 0x1db9470 VA: 0x75943d1470
	private Void _InitIfNot() { }
	// RVA: 0x1db99e0 VA: 0x75943d19e0
	private Void _ResetData() { }
	// RVA: 0x1dbaf98 VA: 0x75943d2f98
	private Void _ResetReshuffleBeforePlay() { }
	// RVA: 0x1db9f20 VA: 0x75943d1f20
	private Void _UpdateReshufflePart() { }
	// RVA: 0x1db9c5c VA: 0x75943d1c5c
	private Void _UpdateUsedCardPart(Int32 targetUsedCardCount) { }
	// RVA: 0x1db9dd0 VA: 0x75943d1dd0
	private Void _UpdateRemainCardPart(Int32 targetRemainNum) { }
	// RVA: 0x1dba0b8 VA: 0x75943d20b8
	private Void _UpdateGoldDrawPart(Int32 targetGoldNum, Int32 drawNeedGoldPrice, Boolean isCardFull) { }
	// RVA: 0x1dbb048 VA: 0x75943d3048
	private GOLD_DRAW_STATE _GetDrawState(Boolean glowing, Boolean isCardFull) { }
	// RVA: 0x1dbb19c VA: 0x75943d319c
	private Void _UpdateGoldDrawPartText(GOLD_DRAW_STATE drawState, Boolean glowing, Int32 targetGoldNum, Int32 drawNeedGoldPrice) { }
	// RVA: 0x1dbb4bc VA: 0x75943d34bc
	private Void _UpdateGoldDrawPartState(GOLD_DRAW_STATE drawState) { }
	// RVA: 0x1dbbec0 VA: 0x75943d3ec0
	private Void _CardFullPutToUsed(LegionModeOnCardFullParam param) { }
	// RVA: 0x1dbbf5c VA: 0x75943d3f5c
	public Void OnDestroy() { }
	// RVA: 0x1dbc0a0 VA: 0x75943d40a0
	public Void .ctor() { }
	// RVA: 0x1dbc128 VA: 0x75943d4128
	private static Void .cctor() { }
}
```