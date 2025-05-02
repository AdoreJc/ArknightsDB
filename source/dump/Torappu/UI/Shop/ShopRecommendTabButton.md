# ShopRecommendTabButton

**Namespace:** `Torappu.UI.Shop`


## Fields

- `Text _buttonText`

- `Text _buttonText_2`

- `GameObject _selectPart`

- `GameObject _unselectPart`

- `GameObject _onSaleTag`

- `GameObject _newTag`

- `GameObject _timeLimitTag`

- `UIStringEvent onClickEvent`

- `String m_cacheId`

- `ShopRecommendViewModel cacheData`


## Methods

- `Void RenderButton(ShopRecommendViewModel)`

- `Boolean SetSelectedState(String)`

- `Void RefreshTagState(ShopRecommendViewModel)`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class ShopRecommendTabButton : MonoBehaviour, IHotfixable
{
	private Text _buttonText; // 0x18
	private Text _buttonText_2; // 0x20
	private GameObject _selectPart; // 0x28
	private GameObject _unselectPart; // 0x30
	private GameObject _onSaleTag; // 0x38
	private GameObject _newTag; // 0x40
	private GameObject _timeLimitTag; // 0x48
	public UIStringEvent onClickEvent; // 0x50
	private String m_cacheId; // 0x58
	public ShopRecommendViewModel cacheData; // 0x60
	private static DelegateBridge __Hotfix0_RenderButton; // 0x0
	private static DelegateBridge __Hotfix0_SetSelectedState; // 0x8
	private static DelegateBridge __Hotfix0_RefreshTagState; // 0x10
	private static DelegateBridge __Hotfix0_OnClick; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x245e170 VA: 0x7594a76170
	public Void RenderButton(ShopRecommendViewModel buttonViewModel) { }
	// RVA: 0x245e368 VA: 0x7594a76368
	public Boolean SetSelectedState(String tabId) { }
	// RVA: 0x245e26c VA: 0x7594a7626c
	public Void RefreshTagState(ShopRecommendViewModel currentViewModel) { }
	// RVA: 0x245e494 VA: 0x7594a76494
	public Void OnClick() { }
	// RVA: 0x245e528 VA: 0x7594a76528
	public Void .ctor() { }
}
```