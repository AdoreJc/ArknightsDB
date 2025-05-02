# UICardEffectHolder

**Namespace:** `Torappu.Battle.UI`


## Fields

- `Image _comboImageOutline`

- `GameObject _durangeImage`

- `GameObject _tauntImage`

- `GameObject _devouredImage`

- `GameObject _mutationImage`

- `GameObject _selectImage`

- `GameObject _wtrmanDisturbImage`

- `GameObject _chosenOneImage`

- `GameObject _ascensionImage`

- `RectTransform m_rectTransform`

- `RectTransform m_targetRectTransform`


## Methods

- `Void UpdateState(UICard)`

- `Void UpdateEffect(UICard)`

- `Void ShowSelectImage(Boolean)`

- `Void Awake()`

- `Void UpdateCardEffectPlugin(Card)`

- `Void RemoveCardEffectPlugin(CardEffectPlugin)`

- `Void <>xLuaBaseProxy_Update()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class UICardEffectHolder : UIFollower
{
	private Image _comboImageOutline; // 0x40
	private GameObject _durangeImage; // 0x48
	private GameObject _tauntImage; // 0x50
	private GameObject _devouredImage; // 0x58
	private GameObject _mutationImage; // 0x60
	private GameObject _selectImage; // 0x68
	private GameObject _wtrmanDisturbImage; // 0x70
	private GameObject _chosenOneImage; // 0x78
	private GameObject _ascensionImage; // 0x80
	private RectTransform m_rectTransform; // 0x88
	private RectTransform m_targetRectTransform; // 0x90
	private List`1 m_plugins; // 0x98
	private static DelegateBridge __Hotfix0_UpdateState; // 0x0
	private static DelegateBridge __Hotfix0_UpdateEffect; // 0x8
	private static DelegateBridge __Hotfix0_ShowSelectImage; // 0x10
	private static DelegateBridge __Hotfix0_Update; // 0x18
	private static DelegateBridge __Hotfix0_Awake; // 0x20
	private static DelegateBridge __Hotfix0_UpdateCardEffectPlugin; // 0x28
	private static DelegateBridge __Hotfix0_RemoveCardEffectPlugin; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x202c224 VA: 0x7594644224
	public Void UpdateState(UICard card) { }
	// RVA: 0x202c3ec VA: 0x75946443ec
	public Void UpdateEffect(UICard card) { }
	// RVA: 0x202cc7c VA: 0x7594644c7c
	public Void ShowSelectImage(Boolean isShow) { }
	// RVA: 0x202e5fc VA: 0x75946465fc
	public override Void Update() { }
	// RVA: 0x202e6d8 VA: 0x75946466d8
	private Void Awake() { }
	// RVA: 0x202e790 VA: 0x7594646790
	public Void UpdateCardEffectPlugin(Card card) { }
	// RVA: 0x202ecf0 VA: 0x7594646cf0
	public Void RemoveCardEffectPlugin(CardEffectPlugin plugin) { }
	// RVA: 0x202ed90 VA: 0x7594646d90
	public Void .ctor() { }
	// RVA: 0x202ee54 VA: 0x7594646e54
	private Void <>xLuaBaseProxy_Update() { }
}
```