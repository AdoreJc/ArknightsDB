# MiniActTrialRewardItemView

**Namespace:** `Torappu.UI.StoryReview`


## Fields

- `Single _completedAlpha`

- `CanvasGroup _alphaHandler`

- `GameObject _gotPartGo`

- `RectTransform _itemParent`

- `Single _itemScale`

- `Text _textName`

- `Text _textCount`

- `Image _imgCross`

- `Text _textDeco1`

- `Text _textDeco2`

- `GameObject _btnCollectGo`

- `GameObject _unachievePartGo`

- `Color _colorUnachieveItemText`

- `Color _colorUnachieveDecoText`

- `Color _colorUnachieveGotDecoText`

- `GameObject _achievePartGo`

- `Color _colorAchieveItemText`

- `Color _colorAchieveDecoText`

- `Color _colorAchieveGotDecoText`

- `Image _imgTheme`

- `Image _imgBlink`

- `MiniActTrialRewardItemModel m_rewardModel`

- `UIItemCard m_itemCard`

- `UIItemViewModel m_rewardViewModel`


## Methods

- `Void set_onTrialCollect(Action`2)`

- `Void Render(MiniActTrialRewardItemModel)`

- `Void OnTrialCollect()`

- `Void <Render>b__28_0(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.StoryReview
public class MiniActTrialRewardItemView : MonoBehaviour, IHotfixable
{
	private Single _completedAlpha; // 0x18
	private CanvasGroup _alphaHandler; // 0x20
	private GameObject _gotPartGo; // 0x28
	private RectTransform _itemParent; // 0x30
	private Single _itemScale; // 0x38
	private Text _textName; // 0x40
	private Text _textCount; // 0x48
	private Image _imgCross; // 0x50
	private Text _textDeco1; // 0x58
	private Text _textDeco2; // 0x60
	private GameObject _btnCollectGo; // 0x68
	private GameObject _unachievePartGo; // 0x70
	private Color _colorUnachieveItemText; // 0x78
	private Color _colorUnachieveDecoText; // 0x88
	private Color _colorUnachieveGotDecoText; // 0x98
	private GameObject _achievePartGo; // 0xa8
	private Color _colorAchieveItemText; // 0xb0
	private Color _colorAchieveDecoText; // 0xc0
	private Color _colorAchieveGotDecoText; // 0xd0
	private Image _imgTheme; // 0xe0
	private Image _imgBlink; // 0xe8
	private MiniActTrialRewardItemModel m_rewardModel; // 0xf0
	private UIItemCard m_itemCard; // 0xf8
	private UIItemViewModel m_rewardViewModel; // 0x100
	private Action`2 <onTrialCollect>k__BackingField; // 0x108
	private static DelegateBridge __Hotfix0_get_onTrialCollect; // 0x0
	private static DelegateBridge __Hotfix0_set_onTrialCollect; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_OnTrialCollect; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private Action`2 onTrialCollect { get; set; }

	// RVA: 0x274b5c4 VA: 0x7594d635c4
	private Action`2 get_onTrialCollect() { }
	// RVA: 0x274ab60 VA: 0x7594d62b60
	public Void set_onTrialCollect(Action`2 value) { }
	// RVA: 0x274abe4 VA: 0x7594d62be4
	public Void Render(MiniActTrialRewardItemModel rewardItemModel) { }
	// RVA: 0x274b910 VA: 0x7594d63910
	public Void OnTrialCollect() { }
	// RVA: 0x274bb88 VA: 0x7594d63b88
	public Void .ctor() { }
	// RVA: 0x274bc50 VA: 0x7594d63c50
	private Void <Render>b__28_0(Int32 index) { }
}
```