# ActMultiV3PrepareMainCharCard

**Namespace:** `Torappu.Activity.ActMultiV3.Prepare`


## Fields

- `TwoStateToggle _cardToggle`

- `ActMultiV3CharCardBase _cardPrefab`

- `Transform _container`

- `UIColorGraphic _btnGraphic`

- `GameObject _disactiveFlag`

- `TwoStateToggle _btnSkip`

- `Text _skipNum`

- `ActMultiV3CharCardBase m_card`

- `ActMultiV3PrepareMainCharCardModel m_cachedModel`

- `Action m_confirmSkip`

- `Coroutine m_skipResumeCoroutine`

- `Boolean <tempTagValid>k__BackingField`


## Properties

- `Boolean enableClick`

- `Action onSkip`

- `Boolean tempTagValid`


## Methods

- `Void set_enableClick(Boolean)`

- `Void set_onClick(Action`1)`

- `Void set_onSkip(Action)`

- `Boolean get_tempTagValid()`

- `Void RenderCard(ActMultiV3PrepareMainCharCardModel)`

- `Void _InitIfNot()`

- `Void EventOnClick()`

- `Void EventOnSkipClick()`

- `IEnumerator _ResumeSkipBtn()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3.Prepare
public class ActMultiV3PrepareMainCharCard : MonoBehaviour, IHotfixable
{
	private TwoStateToggle _cardToggle; // 0x18
	private ActMultiV3CharCardBase _cardPrefab; // 0x20
	private Transform _container; // 0x28
	private UIColorGraphic _btnGraphic; // 0x30
	private GameObject _disactiveFlag; // 0x38
	private TwoStateToggle _btnSkip; // 0x40
	private Text _skipNum; // 0x48
	private ActMultiV3CharCardBase m_card; // 0x50
	private Action`1 m_clickListener; // 0x58
	private ActMultiV3PrepareMainCharCardModel m_cachedModel; // 0x60
	private Action m_confirmSkip; // 0x68
	private Coroutine m_skipResumeCoroutine; // 0x70
	private const Single BTN_SKIP_RESUME_DELAY; // 0x0
	private Boolean <tempTagValid>k__BackingField; // 0x78
	private static DelegateBridge __Hotfix0_set_enableClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onClick; // 0x8
	private static DelegateBridge __Hotfix0_set_onSkip; // 0x10
	private static DelegateBridge __Hotfix0_get_tempTagValid; // 0x18
	private static DelegateBridge __Hotfix0_set_tempTagValid; // 0x20
	private static DelegateBridge __Hotfix0_RenderCard; // 0x28
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge __Hotfix0_EventOnClick; // 0x38
	private static DelegateBridge __Hotfix0_EventOnSkipClick; // 0x40
	private static DelegateBridge __Hotfix0__ResumeSkipBtn; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public Boolean enableClick { set; }
	public Action`1 onClick { set; }
	public Action onSkip { set; }
	public Boolean tempTagValid { get; set; }

	// RVA: 0x315e96c VA: 0x759577696c
	public Void set_enableClick(Boolean value) { }
	// RVA: 0x315ea04 VA: 0x7595776a04
	public Void set_onClick(Action`1 value) { }
	// RVA: 0x315ea88 VA: 0x7595776a88
	public Void set_onSkip(Action value) { }
	// RVA: 0x315eb0c VA: 0x7595776b0c
	public Boolean get_tempTagValid() { }
	// RVA: 0x315eb74 VA: 0x7595776b74
	internal Void set_tempTagValid(Boolean value) { }
	// RVA: 0x315ebf4 VA: 0x7595776bf4
	public Void RenderCard(ActMultiV3PrepareMainCharCardModel model) { }
	// RVA: 0x315ed58 VA: 0x7595776d58
	private Void _InitIfNot() { }
	// RVA: 0x315ee88 VA: 0x7595776e88
	public Void EventOnClick() { }
	// RVA: 0x315ef98 VA: 0x7595776f98
	public Void EventOnSkipClick() { }
	// RVA: 0x315f0a0 VA: 0x75957770a0
	private IEnumerator _ResumeSkipBtn() { }
	// RVA: 0x315f174 VA: 0x7595777174
	public Void .ctor() { }
}
```