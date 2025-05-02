# TuningBagCardGroupItemView

**Namespace:** `Torappu.UI.Tuning`


## Fields

- `SimpleLayoutContent _cardContent`

- `Text _formDescText`

- `TuningProductBagFormModel m_cachedFormModel`

- `Color m_cachedColor`

- `Boolean m_isInited`

- `CardAdapter m_cardAdapter`


## Methods

- `Void Render(TuningProductBagFormModel)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Tuning
public class TuningBagCardGroupItemView : MonoBehaviour, IHotfixable
{
	private SimpleLayoutContent _cardContent; // 0x18
	private Text _formDescText; // 0x20
	private TuningProductBagFormModel m_cachedFormModel; // 0x28
	private Color m_cachedColor; // 0x30
	private Boolean m_isInited; // 0x40
	private CardAdapter m_cardAdapter; // 0x48
	public Action`1 onSelectCard; // 0x50
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x233eb74 VA: 0x7594956b74
	public Void Render(TuningProductBagFormModel formModel) { }
	// RVA: 0x233ec60 VA: 0x7594956c60
	private Void _InitIfNot() { }
	// RVA: 0x233ee2c VA: 0x7594956e2c
	public Void .ctor() { }
}
```