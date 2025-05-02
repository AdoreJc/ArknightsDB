# Act20sideEntertainCompetitionView

**Namespace:** `Torappu.Activity.Act20side`


## Fields

- `GameObject _panelValidStage1`

- `Text _txtDescStage1`

- `UIAtlasImage _imgRankStage1`

- `GameObject _panelLockStage1`

- `Text _txtUnlockStage1`

- `RectTransform _panelNewStage1`

- `GameObject _panelValidStage2`

- `Text _txtDescStage2`

- `UIAtlasImage _imgRankStage2`

- `GameObject _panelLockStage2`

- `Text _txtUnlockStage2`

- `RectTransform _panelNewStage2`

- `GameObject _trackPointPrefab`

- `UIAtlasObject _rankImageObject`

- `Boolean m_hasInited`

- `GameObject m_trackPointStage1`

- `GameObject m_trackPointStage2`


## Methods

- `Void Render(Act20sideEntertainCompViewModel, Boolean)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act20side
public class Act20sideEntertainCompetitionView : MonoBehaviour, IHotfixable
{
	private GameObject _panelValidStage1; // 0x18
	private Text _txtDescStage1; // 0x20
	private UIAtlasImage _imgRankStage1; // 0x28
	private GameObject _panelLockStage1; // 0x30
	private Text _txtUnlockStage1; // 0x38
	private RectTransform _panelNewStage1; // 0x40
	private GameObject _panelValidStage2; // 0x48
	private Text _txtDescStage2; // 0x50
	private UIAtlasImage _imgRankStage2; // 0x58
	private GameObject _panelLockStage2; // 0x60
	private Text _txtUnlockStage2; // 0x68
	private RectTransform _panelNewStage2; // 0x70
	private GameObject _trackPointPrefab; // 0x78
	private List`1 _rankImageName; // 0x80
	private UIAtlasObject _rankImageObject; // 0x88
	private Boolean m_hasInited; // 0x90
	private GameObject m_trackPointStage1; // 0x98
	private GameObject m_trackPointStage2; // 0xa0
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x32f73ec VA: 0x759590f3ec
	public Void Render(Act20sideEntertainCompViewModel viewModel, Boolean isRetro) { }
	// RVA: 0x3300384 VA: 0x7595918384
	private Void _InitIfNot() { }
	// RVA: 0x330048c VA: 0x759591848c
	public Void .ctor() { }
}
```