# InfoDefaultState

**Namespace:** `Torappu.UI.Info`


## Fields

- `UICommonTrackPoint _handbookTrackPoint`

- `UICommonTrackPoint _medalTrackPoint`

- `UICommonTrackPoint _storyReviewTrackPoint`

- `UICommonTrackPoint _handbookUpdatedTrackPoint`

- `UICommonTrackPoint _trainingCampTrackPoint`

- `UICommonTrackPoint _uniEquipArchiveTrackPoint`

- `TwoStateToggle _wardrobeEntryBtn`

- `TwoStateToggle _trainingCampBtn`

- `TrackPointViewProperty m_handbooktrackModel`

- `TrackPointViewProperty m_medalTrackModel`

- `TrackPointViewProperty m_storyReviewTrackModel`

- `TrackPointViewProperty m_handbookupdatedModel`

- `TrackPointViewProperty m_trainingCampModel`

- `TrackPointViewProperty m_uniEquipArchiveModel`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void OnClickHandbook()`

- `Void OnClickEnemy()`

- `Void OnClickWardrobe()`

- `Void OnClickMedal()`

- `Void OnClickStory()`

- `Void OnClickTrainingCamp()`

- `Void OnClickUniEquipArchive()`

- `Void OnClickLockedWardrobe()`

- `Void OnClickLockedTrainingCamp()`

- `Void _OnJumpToEnemyHandBook(IStateBean)`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Info
public class InfoDefaultState : State
{
	private UICommonTrackPoint _handbookTrackPoint; // 0x50
	private UICommonTrackPoint _medalTrackPoint; // 0x58
	private UICommonTrackPoint _storyReviewTrackPoint; // 0x60
	private UICommonTrackPoint _handbookUpdatedTrackPoint; // 0x68
	private UICommonTrackPoint _trainingCampTrackPoint; // 0x70
	private UICommonTrackPoint _uniEquipArchiveTrackPoint; // 0x78
	private TwoStateToggle _wardrobeEntryBtn; // 0x80
	private TwoStateToggle _trainingCampBtn; // 0x88
	private TrackPointViewProperty m_handbooktrackModel; // 0x90
	private TrackPointViewProperty m_medalTrackModel; // 0x98
	private TrackPointViewProperty m_storyReviewTrackModel; // 0xa0
	private TrackPointViewProperty m_handbookupdatedModel; // 0xa8
	private TrackPointViewProperty m_trainingCampModel; // 0xb0
	private TrackPointViewProperty m_uniEquipArchiveModel; // 0xb8
	private Boolean m_isInited; // 0xc0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnResume; // 0x8
	private static DelegateBridge __Hotfix0_OnClickHandbook; // 0x10
	private static DelegateBridge __Hotfix0_OnClickEnemy; // 0x18
	private static DelegateBridge __Hotfix0_OnClickWardrobe; // 0x20
	private static DelegateBridge __Hotfix0_OnClickMedal; // 0x28
	private static DelegateBridge __Hotfix0_OnClickStory; // 0x30
	private static DelegateBridge __Hotfix0_OnClickTrainingCamp; // 0x38
	private static DelegateBridge __Hotfix0_OnClickUniEquipArchive; // 0x40
	private static DelegateBridge __Hotfix0_OnClickLockedWardrobe; // 0x48
	private static DelegateBridge __Hotfix0_OnClickLockedTrainingCamp; // 0x50
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x58
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x60
	private static DelegateBridge __Hotfix0__OnJumpToEnemyHandBook; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70


	// RVA: 0x27b9bcc VA: 0x7594dd1bcc
	private Void _InitIfNot() { }
	// RVA: 0x27b9cd0 VA: 0x7594dd1cd0
	protected override Void OnResume() { }
	// RVA: 0x27b9f5c VA: 0x7594dd1f5c
	public Void OnClickHandbook() { }
	// RVA: 0x27b9fdc VA: 0x7594dd1fdc
	public Void OnClickEnemy() { }
	// RVA: 0x27ba0e8 VA: 0x7594dd20e8
	public Void OnClickWardrobe() { }
	// RVA: 0x27ba16c VA: 0x7594dd216c
	public Void OnClickMedal() { }
	// RVA: 0x27ba1ec VA: 0x7594dd21ec
	public Void OnClickStory() { }
	// RVA: 0x27ba26c VA: 0x7594dd226c
	public Void OnClickTrainingCamp() { }
	// RVA: 0x27ba34c VA: 0x7594dd234c
	public Void OnClickUniEquipArchive() { }
	// RVA: 0x27ba3cc VA: 0x7594dd23cc
	public Void OnClickLockedWardrobe() { }
	// RVA: 0x27ba438 VA: 0x7594dd2438
	public Void OnClickLockedTrainingCamp() { }
	// RVA: 0x27ba4a4 VA: 0x7594dd24a4
	public override IStateBean GetCacheBean() { }
	// RVA: 0x27ba508 VA: 0x7594dd2508
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x27ba680 VA: 0x7594dd2680
	private Void _OnJumpToEnemyHandBook(IStateBean stateBean) { }
	// RVA: 0x27baae0 VA: 0x7594dd2ae0
	public Void .ctor() { }
	// RVA: 0x27bac58 VA: 0x7594dd2c58
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x27bac60 VA: 0x7594dd2c60
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```