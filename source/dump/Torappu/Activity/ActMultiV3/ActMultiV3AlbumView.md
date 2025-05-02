# ActMultiV3AlbumView

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `SimpleLayoutContent _weekTabContent`

- `SimpleLayoutContent _photoContent`

- `Text _collectPhotoCnt`

- `Text _totalPhotoCnt`

- `SimpleLayoutContent _rewardContent`

- `GameObject _cantClaimGo`

- `GameObject _canClaimGo`

- `GameObject _confirmedGo`

- `Boolean m_inited`

- `Int32 m_cachedInitSeqNum`

- `Int32 m_cachedRenderSeqNum`

- `String m_cachedWeekRewardId`

- `WeekTabAdapter m_weekTabAdapter`

- `PhotoAdapter m_photoAdapter`

- `PhotoRewardAdapter m_photoRewardAdapter`

- `UIStateFinder m_stateFinder`


## Methods

- `Void OnClaimAlbum()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3AlbumView : ActMultiV3TabContentAbstractView
{
	private SimpleLayoutContent _weekTabContent; // 0x18
	private SimpleLayoutContent _photoContent; // 0x20
	private Text _collectPhotoCnt; // 0x28
	private Text _totalPhotoCnt; // 0x30
	private SimpleLayoutContent _rewardContent; // 0x38
	private GameObject _cantClaimGo; // 0x40
	private GameObject _canClaimGo; // 0x48
	private GameObject _confirmedGo; // 0x50
	private Boolean m_inited; // 0x58
	private Int32 m_cachedInitSeqNum; // 0x5c
	private Int32 m_cachedRenderSeqNum; // 0x60
	private String m_cachedWeekRewardId; // 0x68
	private WeekTabAdapter m_weekTabAdapter; // 0x70
	private PhotoAdapter m_photoAdapter; // 0x78
	private PhotoRewardAdapter m_photoRewardAdapter; // 0x80
	private UIStateFinder m_stateFinder; // 0x88
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_OnClaimAlbum; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x3118e3c VA: 0x7595730e3c
	public override Void Render(ActMultiV3ManualViewModel viewModel) { }
	// RVA: 0x3119224 VA: 0x7595731224
	public Void OnClaimAlbum() { }
	// RVA: 0x3119060 VA: 0x7595731060
	private Void _InitIfNot() { }
	// RVA: 0x3119314 VA: 0x7595731314
	public Void .ctor() { }
}
```