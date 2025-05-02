# Act12D6RelicHandBookView

**Namespace:** `Torappu.Activity.Act12D6`


## Fields

- `Act12D6RelicHandBookGridAdapter _relicHandBookAdapter`

- `Image _imgIcon`

- `Text _textName`

- `Text _textEffect`

- `Text _textDesc`

- `Text _textCondition`

- `GameObject _imgLock`

- `GameObject _objUnlockTips`

- `Text _relicCount`

- `Text _textChooseTip`

- `Act12D6RelicHandBookStateBean m_cachedBean`


## Methods

- `Void Render(Act12D6RelicHandBookStateBean, String)`

- `Void _RenderEmptyDetailPart()`

- `Void _RenderDetailPart(String)`

- `String _GenerateRelicProgress(PlayerRelicHandBookData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act12D6
public class Act12D6RelicHandBookView : MonoBehaviour, IHotfixable
{
	private Act12D6RelicHandBookGridAdapter _relicHandBookAdapter; // 0x18
	private Image _imgIcon; // 0x20
	private Text _textName; // 0x28
	private Text _textEffect; // 0x30
	private Text _textDesc; // 0x38
	private Text _textCondition; // 0x40
	private GameObject _imgLock; // 0x48
	private GameObject _objUnlockTips; // 0x50
	private Text _relicCount; // 0x58
	private Text _textChooseTip; // 0x60
	private Act12D6RelicHandBookStateBean m_cachedBean; // 0x68
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__RenderEmptyDetailPart; // 0x8
	private static DelegateBridge __Hotfix0__RenderDetailPart; // 0x10
	private static DelegateBridge __Hotfix0__GenerateRelicProgress; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x347867c VA: 0x7595a9067c
	public Void Render(Act12D6RelicHandBookStateBean stateBean, String chosen) { }
	// RVA: 0x3478c98 VA: 0x7595a90c98
	private Void _RenderEmptyDetailPart() { }
	// RVA: 0x347894c VA: 0x7595a9094c
	private Void _RenderDetailPart(String relicId) { }
	// RVA: 0x3478efc VA: 0x7595a90efc
	private String _GenerateRelicProgress(PlayerRelicHandBookData relic) { }
	// RVA: 0x3479014 VA: 0x7595a91014
	public Void .ctor() { }
}
```