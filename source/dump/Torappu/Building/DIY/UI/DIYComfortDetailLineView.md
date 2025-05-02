# DIYComfortDetailLineView

**Namespace:** `Torappu.Building.DIY.UI`


## Fields

- `Text _label0`

- `Text _label1`

- `Text _label2`

- `Color _highlightColor`

- `Color _normalColor`

- `Color _label2ZeroColor`

- `Color m_label2OriginColor`


## Methods

- `Void Awake()`

- `Void Setup(DIYComfortDetailLine)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY.UI
public class DIYComfortDetailLineView : MonoBehaviour, IHotfixable
{
	private Text _label0; // 0x18
	private Text _label1; // 0x20
	private Text _label2; // 0x28
	private GameObject[] _highlight; // 0x30
	private Color _highlightColor; // 0x38
	private Color _normalColor; // 0x48
	private Color _label2ZeroColor; // 0x58
	private Color m_label2OriginColor; // 0x68
	private static DelegateBridge __Hotfix0_Awake; // 0x0
	private static DelegateBridge __Hotfix0_Setup; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x3813c10 VA: 0x7595e2bc10
	private Void Awake() { }
	// RVA: 0x38139cc VA: 0x7595e2b9cc
	public Void Setup(DIYComfortDetailLine line) { }
	// RVA: 0x3813c98 VA: 0x7595e2bc98
	public Void .ctor() { }
}
```