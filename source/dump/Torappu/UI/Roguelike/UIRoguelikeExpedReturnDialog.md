# UIRoguelikeExpedReturnDialog

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Text _charText`

- `Text _detailText`

- `GameObject _pnlClose`

- `GameObject _pnlNext`

- `GameObject _imgExped`

- `GameObject _imgTravel`

- `UIAnimationLocation _animEnter`

- `Action m_onConfirmed`

- `ExpeditionReturnData m_cachedData`

- `Boolean m_waitForConfirm`

- `Int32 m_index`

- `Int32 m_totalCnt`


## Methods

- `Void _RenderSingle()`

- `Void OnConfirmed()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class UIRoguelikeExpedReturnDialog : UICustomDialog`1
{
	private Text _charText; // 0x50
	private Text _detailText; // 0x58
	private GameObject _pnlClose; // 0x60
	private GameObject _pnlNext; // 0x68
	private GameObject _imgExped; // 0x70
	private GameObject _imgTravel; // 0x78
	private UIAnimationLocation _animEnter; // 0x80
	private Action m_onConfirmed; // 0x90
	private ExpeditionReturnData m_cachedData; // 0x98
	private Boolean m_waitForConfirm; // 0xa0
	private Int32 m_index; // 0xa4
	private Int32 m_totalCnt; // 0xa8
	private static DelegateBridge __Hotfix0__RenderSingle; // 0x0
	private static DelegateBridge __Hotfix0_OnRender; // 0x8
	private static DelegateBridge __Hotfix0_OnConfirmed; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x29e72b8 VA: 0x7594fff2b8
	private Void _RenderSingle() { }
	// RVA: 0x29e75c0 VA: 0x7594fff5c0
	protected override Void OnRender(Options options) { }
	// RVA: 0x29e7bb8 VA: 0x7594fffbb8
	public Void OnConfirmed() { }
	// RVA: 0x29e7c68 VA: 0x7594fffc68
	public Void .ctor() { }
}
```