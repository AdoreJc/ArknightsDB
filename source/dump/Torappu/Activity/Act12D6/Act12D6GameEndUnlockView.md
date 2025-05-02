# Act12D6GameEndUnlockView

**Namespace:** `Torappu.Activity.Act12D6`


## Fields

- `SimpleLayoutContent _relicContainer`

- `UIFullScreenImage _imageBlurBkg`

- `Text _textUnlockCnt`

- `Image _imageOutBuffToken`

- `Text _textOutBuffTokenName`

- `Text _textOutBuffTokenCount`

- `Image _imageMilestoneToken`

- `Text _textMilestoneTokenName`

- `Text _textMilestoneTokenCount`

- `Boolean m_inited`

- `Adapter m_adapter`


## Methods

- `Void Render(Act12D6GameEndStateBean)`

- `Void ShotBlurBkg()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act12D6
public class Act12D6GameEndUnlockView : MonoBehaviour, IHotfixable
{
	private const String CNT_FORMAT; // 0x0
	private SimpleLayoutContent _relicContainer; // 0x18
	private UIFullScreenImage _imageBlurBkg; // 0x20
	private Text _textUnlockCnt; // 0x28
	private Image _imageOutBuffToken; // 0x30
	private Text _textOutBuffTokenName; // 0x38
	private Text _textOutBuffTokenCount; // 0x40
	private Image _imageMilestoneToken; // 0x48
	private Text _textMilestoneTokenName; // 0x50
	private Text _textMilestoneTokenCount; // 0x58
	private Boolean m_inited; // 0x60
	private Adapter m_adapter; // 0x68
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_ShotBlurBkg; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x3470ca8 VA: 0x7595a88ca8
	public Void Render(Act12D6GameEndStateBean stateBean) { }
	// RVA: 0x34708d4 VA: 0x7595a888d4
	public Void ShotBlurBkg() { }
	// RVA: 0x3475f64 VA: 0x7595a8df64
	private Void _InitIfNot() { }
	// RVA: 0x347607c VA: 0x7595a8e07c
	public Void .ctor() { }
}
```