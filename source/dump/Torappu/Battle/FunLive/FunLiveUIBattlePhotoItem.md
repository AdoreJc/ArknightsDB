# FunLiveUIBattlePhotoItem

**Namespace:** `Torappu.Battle.FunLive`


## Fields

- `Image _contentPicture`

- `Image _emojiIcon`

- `Transform _normalEventCntTransform`

- `Text _normalEventCnt`

- `Text _photoDescription`

- `Text _tagDescription`

- `FunLiveUIBattlePhotoItemAttributeIcon _pinkIconGroup`

- `FunLiveUIBattlePhotoItemAttributeIcon _yellowIconGroup`

- `FunLiveUIBattlePhotoItemAttributeIcon _blueIconGroup`

- `FunLiveGameMode m_gameMode`

- `Int32 m_levelIndex`


## Methods

- `Void Awake()`

- `Void ApplyData(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.FunLive
public class FunLiveUIBattlePhotoItem : MonoBehaviour, IHotfixable
{
	private Image _contentPicture; // 0x18
	private Image _emojiIcon; // 0x20
	private Transform _normalEventCntTransform; // 0x28
	private Text _normalEventCnt; // 0x30
	private Text _photoDescription; // 0x38
	private Text _tagDescription; // 0x40
	private FunLiveUIBattlePhotoItemAttributeIcon _pinkIconGroup; // 0x48
	private FunLiveUIBattlePhotoItemAttributeIcon _yellowIconGroup; // 0x50
	private FunLiveUIBattlePhotoItemAttributeIcon _blueIconGroup; // 0x58
	private Dictionary`2 m_normalDataList; // 0x60
	private Dictionary`2 m_rareDataList; // 0x68
	private Dictionary`2 m_rareValueDataList; // 0x70
	private FunLiveGameMode m_gameMode; // 0x78
	private Int32 m_levelIndex; // 0x80
	private static DelegateBridge __Hotfix0_Awake; // 0x0
	private static DelegateBridge __Hotfix0_ApplyData; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x1c5aeb0 VA: 0x7594272eb0
	private Void Awake() { }
	// RVA: 0x1c5b054 VA: 0x7594273054
	public Void ApplyData(String ev) { }
	// RVA: 0x1c5ba04 VA: 0x7594273a04
	public Void .ctor() { }
}
```