# UICharacterCardPanel

**Namespace:** `Torappu.UI`


## Fields

- `UIAtlasImage _imageChrPortrait`

- `Image _iconProfession`

- `GameObject _panelSkill`

- `GameObject _panelNoSkill`

- `Image _iconSkill`

- `GameObject _panelPotential`

- `Image _iconPotential`

- `Image _iconEvolve`

- `GameObject _panelUniequip`

- `Image _iconUniequip`

- `Text _textLevel`

- `Image _imageLvlPercent`

- `Text _textRealName`

- `Image _imageStarMark`

- `Image _imgCustomMark`

- `UICharCardRankWidget _panelStars`

- `UICharRarityImage _panelUpperHub`

- `UICharRarityImage _panelLowerHub`

- `UICharRarityImage _panelRarityLight`

- `UICharRarityImage _panelBkg`

- `String m_skillIdCache`

- `String m_portraitCache`

- `String m_uniequipCache`

- `BasicCharInfoModel m_infoCache`


## Methods

- `Void AsyncSetData(AsyncParams)`

- `Void UpdateViewData(CharacterCardViewModel, Options)`

- `Void set_onClick(Action`1)`

- `Void OnCardClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UICharacterCardPanel : MonoBehaviour, IHotfixable, IAsyncDataView`1
{
	private UIAtlasImage _imageChrPortrait; // 0x18
	private Image _iconProfession; // 0x20
	private GameObject _panelSkill; // 0x28
	private GameObject _panelNoSkill; // 0x30
	private Image _iconSkill; // 0x38
	private GameObject _panelPotential; // 0x40
	private Image _iconPotential; // 0x48
	private Image _iconEvolve; // 0x50
	private GameObject _panelUniequip; // 0x58
	private Image _iconUniequip; // 0x60
	private Text _textLevel; // 0x68
	private Image _imageLvlPercent; // 0x70
	private Text _textRealName; // 0x78
	private Image _imageStarMark; // 0x80
	private Image _imgCustomMark; // 0x88
	private UICharCardRankWidget _panelStars; // 0x90
	private UICharRarityImage _panelUpperHub; // 0x98
	private UICharRarityImage _panelLowerHub; // 0xa0
	private UICharRarityImage _panelRarityLight; // 0xa8
	private UICharRarityImage _panelBkg; // 0xb0
	private Action`1 m_clickListener; // 0xb8
	private String m_skillIdCache; // 0xc0
	private String m_portraitCache; // 0xc8
	private String m_uniequipCache; // 0xd0
	private BasicCharInfoModel m_infoCache; // 0xd8
	private static DelegateBridge __Hotfix0_AsyncSetData; // 0x0
	private static DelegateBridge __Hotfix0_UpdateViewData; // 0x8
	private static DelegateBridge __Hotfix1_UpdateViewData; // 0x10
	private static DelegateBridge __Hotfix0_set_onClick; // 0x18
	private static DelegateBridge __Hotfix0__IsCharBasicChanged; // 0x20
	private static DelegateBridge __Hotfix0_OnCardClick; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public Action`1 onClick { set; }

	// RVA: 0x212a8d4 VA: 0x75947428d4
	public Void AsyncSetData(AsyncParams data) { }
	// RVA: 0x212a95c VA: 0x759474295c
	public virtual Void UpdateViewData(CharacterCardViewModel viewModel) { }
	// RVA: 0x212aa0c VA: 0x7594742a0c
	public Void UpdateViewData(CharacterCardViewModel viewModel, Options options) { }
	// RVA: 0x212b3d0 VA: 0x75947433d0
	public Void set_onClick(Action`1 value) { }
	// RVA: 0x212b1c8 VA: 0x75947431c8
	private static Boolean _IsCharBasicChanged(BasicCharInfoModel prevInfo, BasicCharInfoModel curInfo) { }
	// RVA: 0x212b454 VA: 0x7594743454
	public Void OnCardClick() { }
	// RVA: 0x212b4e8 VA: 0x75947434e8
	public Void .ctor() { }
}
```