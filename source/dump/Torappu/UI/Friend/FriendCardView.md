# FriendCardView

**Namespace:** `Torappu.UI.Friend`


## Fields

- `UICharacterCardPanel _charCardPrefab`

- `RectTransform _charCardContainer`

- `Single _charCardScale`

- `Image _potentialIcon`

- `CharacterInfoSelectSkillItemView _skillItem`

- `GameObject _charEnable`

- `GameObject _charUnable`

- `GameObject _skillEnable`

- `GameObject _skillUnable`

- `RectTransform _layout`

- `Int32 _index`

- `UICharacterCardPanel m_charCardInst`


## Methods

- `Void Start()`

- `Void ApplyData(SharedCharData, CharacterCardViewModel)`

- `IEnumerator UpdateLayout(RectTransform)`

- `UICharacterCardPanel _EnsureCharCard()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Friend
public class FriendCardView : MonoBehaviour
{
	private UICharacterCardPanel _charCardPrefab; // 0x18
	private RectTransform _charCardContainer; // 0x20
	private Single _charCardScale; // 0x28
	private Image _potentialIcon; // 0x30
	private CharacterInfoSelectSkillItemView _skillItem; // 0x38
	private GameObject _charEnable; // 0x40
	private GameObject _charUnable; // 0x48
	private GameObject _skillEnable; // 0x50
	private GameObject _skillUnable; // 0x58
	private RectTransform _layout; // 0x60
	private Int32 _index; // 0x68
	private UICharacterCardPanel m_charCardInst; // 0x70


	// RVA: 0x28cbaf0 VA: 0x7594ee3af0
	private Void Start() { }
	// RVA: 0x28cbb88 VA: 0x7594ee3b88
	public Void ApplyData(SharedCharData assistFriend, CharacterCardViewModel cardViewModel) { }
	// RVA: 0x28cbb14 VA: 0x7594ee3b14
	private IEnumerator UpdateLayout(RectTransform rect) { }
	// RVA: 0x28cbd9c VA: 0x7594ee3d9c
	private UICharacterCardPanel _EnsureCharCard() { }
	// RVA: 0x28cbed4 VA: 0x7594ee3ed4
	public Void .ctor() { }
}
```