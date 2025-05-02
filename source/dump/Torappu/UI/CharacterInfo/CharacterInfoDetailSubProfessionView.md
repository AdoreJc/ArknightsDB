# CharacterInfoDetailSubProfessionView

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `CharacterInfoDetailTalentContentGroup _contentGroup`

- `Text _subProfName`

- `UICommentedText _subProfDetailBasic`

- `UICommentedText _subProfDetailAdditive`

- `Image _subProfImg`

- `GameObject _uniEquipPart`

- `GameObject _lockedPart`

- `GameObject _haveEquipPart`

- `Text equipName`

- `Text _lockedText`

- `Text _uniEquipName`

- `UICommonEquipTypeIcon _typeIcon`

- `Transform _typeContainer`

- `Transform _container`

- `UniEquipImgHolder _imgHolder`

- `Single _scaleFloat`

- `UniEquipImgHolder m_imgHolder`

- `Boolean m_isInited`

- `UICommonEquipTypeIcon m_typeIcon`


## Methods

- `Void _InitIfNot()`

- `Void Render(CharacterProfileViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterInfoDetailSubProfessionView : MonoBehaviour, IHotfixable
{
	private CharacterInfoDetailTalentContentGroup _contentGroup; // 0x18
	private Text _subProfName; // 0x20
	private UICommentedText _subProfDetailBasic; // 0x28
	private UICommentedText _subProfDetailAdditive; // 0x30
	private Image _subProfImg; // 0x38
	private GameObject _uniEquipPart; // 0x40
	private GameObject _lockedPart; // 0x48
	private GameObject _haveEquipPart; // 0x50
	private Text equipName; // 0x58
	private Text _lockedText; // 0x60
	private Text _uniEquipName; // 0x68
	private UICommonEquipTypeIcon _typeIcon; // 0x70
	private Transform _typeContainer; // 0x78
	private Transform _container; // 0x80
	private UniEquipImgHolder _imgHolder; // 0x88
	private Single _scaleFloat; // 0x90
	private UniEquipImgHolder m_imgHolder; // 0x98
	private Boolean m_isInited; // 0xa0
	private UICommonEquipTypeIcon m_typeIcon; // 0xa8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2d8c768 VA: 0x75953a4768
	private Void _InitIfNot() { }
	// RVA: 0x2d8c880 VA: 0x75953a4880
	public Void Render(CharacterProfileViewModel profileViewModel) { }
	// RVA: 0x2d8cdd8 VA: 0x75953a4dd8
	public Void .ctor() { }
}
```