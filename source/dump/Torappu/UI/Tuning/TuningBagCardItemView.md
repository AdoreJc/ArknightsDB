# TuningBagCardItemView

**Namespace:** `Torappu.UI.Tuning`


## Fields

- `TuningCommonCard _commonCard`

- `Text _orcheName`

- `Text _productNum`

- `UIAtlasImage _cardSelectFrameImg`

- `GameObject _answerFrameObj`

- `Button _cardBtn`

- `String m_cachedProductId`


## Methods

- `Void Render(TuningProductBagCardModel)`

- `Void OnSelectCard()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Tuning
public class TuningBagCardItemView : MonoBehaviour, IHotfixable
{
	private TuningCommonCard _commonCard; // 0x18
	private Text _orcheName; // 0x20
	private Text _productNum; // 0x28
	private UIAtlasImage _cardSelectFrameImg; // 0x30
	private GameObject _answerFrameObj; // 0x38
	private Button _cardBtn; // 0x40
	private String m_cachedProductId; // 0x48
	public Action`1 onSelectCard; // 0x50
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_OnSelectCard; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x233f1f4 VA: 0x75949571f4
	public Void Render(TuningProductBagCardModel bagCardModel) { }
	// RVA: 0x233f648 VA: 0x7594957648
	public Void OnSelectCard() { }
	// RVA: 0x233f6d0 VA: 0x75949576d0
	public Void .ctor() { }
}
```