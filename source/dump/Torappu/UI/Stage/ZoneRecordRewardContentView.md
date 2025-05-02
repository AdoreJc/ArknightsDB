# ZoneRecordRewardContentView

**Namespace:** `Torappu.UI.Stage`


## Fields

- `GameObject _objRewardClaimAll`

- `SimpleLayoutContent _diffRewardLayout`

- `GameObject _objRewardTitle`

- `GameObject _objRewardAllClaimed`

- `CanvasGroup _canvasRewardAllFold`

- `CanvasGroup _canvasRewardAllUnfold`

- `CanvasGroup _canvasRewardsList`

- `CanvasGroup _canvasRewardListMask`

- `UIAtlasImage _iconBg`

- `UIAtlasImage _iconRewardBg`

- `Boolean m_hasInited`

- `ZoneRecordDiffRewardItemAdapter m_rewardListAdapter`

- `RewardFoldSwitchTween m_foldTween`

- `RewardFoldSwitchTween m_unfoldTween`

- `FadeSwitchTween m_rewadsListTween`

- `Boolean m_consumeClaimFlag`

- `String m_cachedZoneId`

- `Action <onClaimAllClick>k__BackingField`

- `ZoneRecordController controller`


## Properties

- `Action onClaimAllClick`


## Methods

- `Action get_onClaimAllClick()`

- `Void set_onClaimAllClick(Action)`

- `Void _InitIfNot()`

- `Void _FoldAllRewards(Boolean, Boolean)`

- `Void _FoldRewardsList(Boolean, Boolean)`

- `Void _LoadBgIcon(String)`

- `Void Render(ZoneRecordGroupViewModel)`

- `Void ResetContentViewBeforeClose()`

- `Void EventOnClaimAllClick()`

- `Void EventOnFoldRewardBtnClick()`

- `Void EventOnUnfoldRewardBtnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class ZoneRecordRewardContentView : MonoBehaviour, IHotfixable
{
	private GameObject _objRewardClaimAll; // 0x18
	private SimpleLayoutContent _diffRewardLayout; // 0x20
	private GameObject _objRewardTitle; // 0x28
	private GameObject _objRewardAllClaimed; // 0x30
	private CanvasGroup _canvasRewardAllFold; // 0x38
	private CanvasGroup _canvasRewardAllUnfold; // 0x40
	private CanvasGroup _canvasRewardsList; // 0x48
	private CanvasGroup _canvasRewardListMask; // 0x50
	private UIAtlasImage _iconBg; // 0x58
	private UIAtlasImage _iconRewardBg; // 0x60
	private Boolean m_hasInited; // 0x68
	private ZoneRecordDiffRewardItemAdapter m_rewardListAdapter; // 0x70
	private RewardFoldSwitchTween m_foldTween; // 0x78
	private RewardFoldSwitchTween m_unfoldTween; // 0x80
	private FadeSwitchTween m_rewadsListTween; // 0x88
	private const Single FOLD_ALPHA_DURATION; // 0x0
	private Boolean m_consumeClaimFlag; // 0x90
	private String m_cachedZoneId; // 0x98
	private const Single ALL_CLAIMED_LIST_TOP_ALPHA; // 0x0
	private Action <onClaimAllClick>k__BackingField; // 0xa0
	public ZoneRecordController controller; // 0xa8
	private static DelegateBridge __Hotfix0_get_onClaimAllClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onClaimAllClick; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__FoldAllRewards; // 0x18
	private static DelegateBridge __Hotfix0__FoldRewardsList; // 0x20
	private static DelegateBridge __Hotfix0__LoadBgIcon; // 0x28
	private static DelegateBridge __Hotfix0_Render; // 0x30
	private static DelegateBridge __Hotfix0_ResetContentViewBeforeClose; // 0x38
	private static DelegateBridge __Hotfix0_EventOnClaimAllClick; // 0x40
	private static DelegateBridge __Hotfix0_EventOnFoldRewardBtnClick; // 0x48
	private static DelegateBridge __Hotfix0_EventOnUnfoldRewardBtnClick; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	public Action onClaimAllClick { get; set; }

	// RVA: 0x2fc14a8 VA: 0x75955d94a8
	public Action get_onClaimAllClick() { }
	// RVA: 0x2fc1510 VA: 0x75955d9510
	public Void set_onClaimAllClick(Action value) { }
	// RVA: 0x2fc1594 VA: 0x75955d9594
	private Void _InitIfNot() { }
	// RVA: 0x2fc17d8 VA: 0x75955d97d8
	private Void _FoldAllRewards(Boolean fold, Boolean directlyShowList) { }
	// RVA: 0x2fc1898 VA: 0x75955d9898
	private Void _FoldRewardsList(Boolean fold, Boolean directly) { }
	// RVA: 0x2fc1950 VA: 0x75955d9950
	private Void _LoadBgIcon(String zoneId) { }
	// RVA: 0x2fc1c5c VA: 0x75955d9c5c
	public Void Render(ZoneRecordGroupViewModel groupViewModel) { }
	// RVA: 0x2fc1edc VA: 0x75955d9edc
	public Void ResetContentViewBeforeClose() { }
	// RVA: 0x2fc1f4c VA: 0x75955d9f4c
	public Void EventOnClaimAllClick() { }
	// RVA: 0x2fc1ff8 VA: 0x75955d9ff8
	public Void EventOnFoldRewardBtnClick() { }
	// RVA: 0x2fc2068 VA: 0x75955da068
	public Void EventOnUnfoldRewardBtnClick() { }
	// RVA: 0x2fc20d8 VA: 0x75955da0d8
	public Void .ctor() { }
}
```