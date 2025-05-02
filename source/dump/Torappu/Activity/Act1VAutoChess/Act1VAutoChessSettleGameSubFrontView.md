# Act1VAutoChessSettleGameSubFrontView

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `RectTransform _backRect`

- `SimpleLayoutContent _equipContent`

- `GameObject _equipNormalPanel`

- `GameObject _equipEmptyPanel`

- `Image _bpItemIconImage`

- `Text _bpItemGainText`

- `BpRewardItem _normalReward`

- `BpRewardItem _extraReward`

- `Act1VAutoChessSettleGameDailyRewardView _dailyReward`

- `Act1VAutoChessSettleGameLevelView _levelView`

- `Act1VAutoChessEntrySettleGameEnterExitAnim _enterExitAnim`

- `Boolean m_hasInited`

- `UIPageFinder m_finder`

- `EquipAdapter m_equipAdapter`

- `Int32 m_cachedSettleSeqNum`

- `Coroutine m_playSettleCoroutine`

- `Boolean m_blockLeave`

- `Boolean m_entryAnimPlaying`


## Methods

- `Void OnClickLeaveBtn()`

- `Void OnEntryAnimComplete()`

- `Void _InitIfNot()`

- `Void _RenderChars(List`1)`

- `Void _RenderEquips(List`1)`

- `Void _RenderRewards(Act1VAutoChessEntrySettleGameViewModel)`

- `IEnumerator _PlaySettleCoroutine(Act1VAutoChessEntrySettleGameViewModel)`

- `Void <>xLuaBaseProxy_Render(Act1VAutoChessEntryBaseSubViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessSettleGameSubFrontView : Act1VAutoChessBaseSubView
{
	private RectTransform _backRect; // 0x18
	private List`1 _charItems; // 0x20
	private SimpleLayoutContent _equipContent; // 0x28
	private GameObject _equipNormalPanel; // 0x30
	private GameObject _equipEmptyPanel; // 0x38
	private Image _bpItemIconImage; // 0x40
	private Text _bpItemGainText; // 0x48
	private BpRewardItem _normalReward; // 0x50
	private BpRewardItem _extraReward; // 0x60
	private Act1VAutoChessSettleGameDailyRewardView _dailyReward; // 0x70
	private Act1VAutoChessSettleGameLevelView _levelView; // 0x78
	private Act1VAutoChessEntrySettleGameEnterExitAnim _enterExitAnim; // 0x80
	private Boolean m_hasInited; // 0x88
	private UIPageFinder m_finder; // 0x90
	private EquipAdapter m_equipAdapter; // 0xa0
	private Int32 m_cachedSettleSeqNum; // 0xa8
	private Coroutine m_playSettleCoroutine; // 0xb0
	private Boolean m_blockLeave; // 0xb8
	private Boolean m_entryAnimPlaying; // 0xb9
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_OnClickLeaveBtn; // 0x8
	private static DelegateBridge __Hotfix0_OnEntryAnimComplete; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__RenderChars; // 0x20
	private static DelegateBridge __Hotfix0__RenderEquips; // 0x28
	private static DelegateBridge __Hotfix0__RenderRewards; // 0x30
	private static DelegateBridge __Hotfix0__PlaySettleCoroutine; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x3349454 VA: 0x7595961454
	public override Void Render(Act1VAutoChessEntryBaseSubViewModel subViewModel) { }
	// RVA: 0x3349ff8 VA: 0x7595961ff8
	public Void OnClickLeaveBtn() { }
	// RVA: 0x334a0fc VA: 0x75959620fc
	public Void OnEntryAnimComplete() { }
	// RVA: 0x334972c VA: 0x759596172c
	private Void _InitIfNot() { }
	// RVA: 0x33498e8 VA: 0x75959618e8
	private Void _RenderChars(List`1 chars) { }
	// RVA: 0x3349b10 VA: 0x7595961b10
	private Void _RenderEquips(List`1 equips) { }
	// RVA: 0x3349c14 VA: 0x7595961c14
	private Void _RenderRewards(Act1VAutoChessEntrySettleGameViewModel model) { }
	// RVA: 0x3349f28 VA: 0x7595961f28
	private IEnumerator _PlaySettleCoroutine(Act1VAutoChessEntrySettleGameViewModel model) { }
	// RVA: 0x334a3b8 VA: 0x75959623b8
	public Void .ctor() { }
	// RVA: 0x334a430 VA: 0x7595962430
	private Void <>xLuaBaseProxy_Render(Act1VAutoChessEntryBaseSubViewModel P0) { }
}
```