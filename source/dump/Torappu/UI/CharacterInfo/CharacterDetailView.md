# CharacterDetailView

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `CharacterInfoIllustController _illustController`

- `CharacterInfoAttributeViewController _attribute`

- `CharacterDetailViewModel _viewModel`

- `Animator _animator`

- `TutorialObjectHolder _tutorialObjHolder`

- `UICommonTrackPoint _skillTrackPoint`

- `UICommonTrackPoint _potentialTrackPoint`

- `TrackPointViewProperty potentialTrackProp`

- `Action onUpLevel`

- `Action onSkillSelect`

- `Action onEvolve`

- `Action onTrans`

- `Action onSpCharMission`

- `Action OnPotential`

- `Action OnSubProf`

- `Action OnUniEquipClick`

- `Action onProfessionDetailClick`

- `Single m_state`

- `Boolean <autoActivateIllust>k__BackingField`

- `Int32 <chrInstIdCache>k__BackingField`


## Properties

- `Single state`

- `Boolean autoActivateIllust`

- `UICharacterIllust illust`

- `Boolean isReachMaxEvolve`

- `CharacterDetailViewModel model`

- `Int32 chrInstIdCache`

- `EvolvePhase evolvePhase`


## Methods

- `Void set_state(Single)`

- `Boolean get_autoActivateIllust()`

- `Void set_autoActivateIllust(Boolean)`

- `UICharacterIllust get_illust()`

- `Boolean get_isReachMaxEvolve()`

- `Void ConsumeNew()`

- `Void TryConsumeSpCharMissionNew()`

- `CharacterDetailViewModel get_model()`

- `CharacterIllustViewModel GetIllustViewModel()`

- `SkillGroupViewModel GetSkillViewModel()`

- `Void Apply(Int32)`

- `Int32 get_chrInstIdCache()`

- `Void set_chrInstIdCache(Int32)`

- `EvolvePhase get_evolvePhase()`

- `Void BtnOnUpLvl()`

- `Void BtnOnSkillSelect()`

- `Void BtnOnEvolve()`

- `Void BtnOnTrans()`

- `Void BtnOnSpCharMission()`

- `Void BtnOnPotential()`

- `Void BtnOnTalent()`

- `Void BtnOnUniEquip()`

- `Void RefreshState(Single)`

- `Void RefreshData()`

- `Void Render(Int32, Int32, Boolean, Boolean, Boolean)`

- `Void OnProfessionDetail()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterDetailView : MonoBehaviour, IHotfixable
{
	private CharacterInfoIllustController _illustController; // 0x18
	private CharacterInfoAttributeViewController _attribute; // 0x20
	private CharacterDetailViewModel _viewModel; // 0x28
	private Animator _animator; // 0x30
	private TutorialObjectHolder _tutorialObjHolder; // 0x38
	private UICommonTrackPoint _skillTrackPoint; // 0x40
	private UICommonTrackPoint _potentialTrackPoint; // 0x48
	public TrackPointViewProperty potentialTrackProp; // 0x50
	public Action onUpLevel; // 0x58
	public Action onSkillSelect; // 0x60
	public Action onEvolve; // 0x68
	public Action onTrans; // 0x70
	public Action onSpCharMission; // 0x78
	public Action OnPotential; // 0x80
	public Action OnSubProf; // 0x88
	public Action OnUniEquipClick; // 0x90
	public Action onProfessionDetailClick; // 0x98
	private Single m_state; // 0xa0
	private Boolean <autoActivateIllust>k__BackingField; // 0xa4
	private Int32 <chrInstIdCache>k__BackingField; // 0xa8
	private static DelegateBridge __Hotfix0_set_state; // 0x0
	private static DelegateBridge __Hotfix0_get_autoActivateIllust; // 0x8
	private static DelegateBridge __Hotfix0_set_autoActivateIllust; // 0x10
	private static DelegateBridge __Hotfix0_get_illust; // 0x18
	private static DelegateBridge __Hotfix0_get_isReachMaxEvolve; // 0x20
	private static DelegateBridge __Hotfix0_ConsumeNew; // 0x28
	private static DelegateBridge __Hotfix0_TryConsumeSpCharMissionNew; // 0x30
	private static DelegateBridge __Hotfix0_get_model; // 0x38
	private static DelegateBridge __Hotfix0_GetIllustViewModel; // 0x40
	private static DelegateBridge __Hotfix0_GetSkillViewModel; // 0x48
	private static DelegateBridge __Hotfix0_Apply; // 0x50
	private static DelegateBridge __Hotfix0_get_chrInstIdCache; // 0x58
	private static DelegateBridge __Hotfix0_set_chrInstIdCache; // 0x60
	private static DelegateBridge __Hotfix0_get_evolvePhase; // 0x68
	private static DelegateBridge __Hotfix0_BtnOnUpLvl; // 0x70
	private static DelegateBridge __Hotfix0_BtnOnSkillSelect; // 0x78
	private static DelegateBridge __Hotfix0_BtnOnEvolve; // 0x80
	private static DelegateBridge __Hotfix0_BtnOnTrans; // 0x88
	private static DelegateBridge __Hotfix0_BtnOnSpCharMission; // 0x90
	private static DelegateBridge __Hotfix0_BtnOnPotential; // 0x98
	private static DelegateBridge __Hotfix0_BtnOnTalent; // 0xa0
	private static DelegateBridge __Hotfix0_BtnOnUniEquip; // 0xa8
	private static DelegateBridge __Hotfix0_RefreshState; // 0xb0
	private static DelegateBridge __Hotfix0_RefreshData; // 0xb8
	private static DelegateBridge __Hotfix0_Render; // 0xc0
	private static DelegateBridge __Hotfix0_OnProfessionDetail; // 0xc8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xd0

	public Single state { set; }
	public Boolean autoActivateIllust { get; set; }
	public UICharacterIllust illust { get; }
	public Boolean isReachMaxEvolve { get; }
	public CharacterDetailViewModel model { get; }
	public Int32 chrInstIdCache { get; set; }
	public EvolvePhase evolvePhase { get; }

	// RVA: 0x2d666b4 VA: 0x759537e6b4
	public Void set_state(Single value) { }
	// RVA: 0x2d66730 VA: 0x759537e730
	public Boolean get_autoActivateIllust() { }
	// RVA: 0x2d66798 VA: 0x759537e798
	public Void set_autoActivateIllust(Boolean value) { }
	// RVA: 0x2d66818 VA: 0x759537e818
	public UICharacterIllust get_illust() { }
	// RVA: 0x2d6688c VA: 0x759537e88c
	public Boolean get_isReachMaxEvolve() { }
	// RVA: 0x2d66900 VA: 0x759537e900
	public Void ConsumeNew() { }
	// RVA: 0x2d6697c VA: 0x759537e97c
	public Void TryConsumeSpCharMissionNew() { }
	// RVA: 0x2d66a5c VA: 0x759537ea5c
	public CharacterDetailViewModel get_model() { }
	// RVA: 0x2d66ac4 VA: 0x759537eac4
	public CharacterIllustViewModel GetIllustViewModel() { }
	// RVA: 0x2d66b4c VA: 0x759537eb4c
	public SkillGroupViewModel GetSkillViewModel() { }
	// RVA: 0x2d66bd4 VA: 0x759537ebd4
	public Void Apply(Int32 selectIllustIndex) { }
	// RVA: 0x2d66c4c VA: 0x759537ec4c
	public Int32 get_chrInstIdCache() { }
	// RVA: 0x2d66cb4 VA: 0x759537ecb4
	private Void set_chrInstIdCache(Int32 value) { }
	// RVA: 0x2d66d30 VA: 0x759537ed30
	public EvolvePhase get_evolvePhase() { }
	// RVA: 0x2d66da4 VA: 0x759537eda4
	public Void BtnOnUpLvl() { }
	// RVA: 0x2d66e28 VA: 0x759537ee28
	public Void BtnOnSkillSelect() { }
	// RVA: 0x2d66eac VA: 0x759537eeac
	public Void BtnOnEvolve() { }
	// RVA: 0x2d66f30 VA: 0x759537ef30
	public Void BtnOnTrans() { }
	// RVA: 0x2d66fb4 VA: 0x759537efb4
	public Void BtnOnSpCharMission() { }
	// RVA: 0x2d67038 VA: 0x759537f038
	public Void BtnOnPotential() { }
	// RVA: 0x2d670bc VA: 0x759537f0bc
	public Void BtnOnTalent() { }
	// RVA: 0x2d67140 VA: 0x759537f140
	public Void BtnOnUniEquip() { }
	// RVA: 0x2d671c4 VA: 0x759537f1c4
	public Void RefreshState(Single state) { }
	// RVA: 0x2d67324 VA: 0x759537f324
	public Void RefreshData() { }
	// RVA: 0x2d67470 VA: 0x759537f470
	public Void Render(Int32 chrinstId, Int32 state, Boolean haveLeft, Boolean haveRight, Boolean initAsTutorialTarget) { }
	// RVA: 0x2d67644 VA: 0x759537f644
	public Void OnProfessionDetail() { }
	// RVA: 0x2d676c8 VA: 0x759537f6c8
	public Void .ctor() { }
}
```