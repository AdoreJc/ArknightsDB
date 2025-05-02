# ShopKeeperPanel

**Namespace:** `Torappu.UI.Shop`


## Fields

- `ShopRecommendStateBean _stateBean`

- `ShopKeeperDialog _dialog`

- `CanvasGroup _alphaHandler`

- `String _shopKeeperId`

- `Boolean m_isLoaded`

- `String m_tagIdOfCurrentWord`

- `ShopKeeperGraphic m_graphicHolder`


## Methods

- `Void InitWithTag(ShopRecommendViewModel)`

- `Void OnRecommendTagClicked(ShopRecommendViewModel)`

- `Void OnThisPanelClicked()`

- `Boolean _LoadIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class ShopKeeperPanel : MonoBehaviour
{
	private const Single INIT_KEEPER_DELAY; // 0x0
	private ShopRecommendStateBean _stateBean; // 0x18
	private ShopKeeperDialog _dialog; // 0x20
	private CanvasGroup _alphaHandler; // 0x28
	private String _shopKeeperId; // 0x30
	private Boolean m_isLoaded; // 0x38
	private String m_tagIdOfCurrentWord; // 0x40
	private ShopKeeperGraphic m_graphicHolder; // 0x48


	// RVA: 0x2467238 VA: 0x7594a7f238
	public Void InitWithTag(ShopRecommendViewModel initTag) { }
	// RVA: 0x2467670 VA: 0x7594a7f670
	public Void OnRecommendTagClicked(ShopRecommendViewModel newTag) { }
	// RVA: 0x24676f0 VA: 0x7594a7f6f0
	public Void OnThisPanelClicked() { }
	// RVA: 0x24673b4 VA: 0x7594a7f3b4
	private Boolean _LoadIfNot() { }
	// RVA: 0x2467830 VA: 0x7594a7f830
	public Void .ctor() { }
}
```