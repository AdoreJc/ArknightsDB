# SandboxV2ChallengeRewardItemView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `GameObject _pnlComplete`

- `GameObject _pnlIncomplete`

- `GameObject _pnlReceived`

- `Text _textDay`

- `Text _textDesc`

- `Color _colorDayComplete`

- `Color _colorDayIncomplete`

- `Color _colorDescComplete`

- `Color _colorDescIncomplete`

- `SimpleLayoutContent _rewardContainer`

- `Single _itemCardScale`

- `Adapter m_adapter`

- `Boolean m_inited`

- `State m_cachedState`

- `String m_cachedRewardId`


## Methods

- `Void set_onReceiveClicked(Action`1)`

- `Void _InitIfNot()`

- `Void Render(SandboxV2ChallengeRewardViewModel)`

- `Void OnReceiveClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2ChallengeRewardItemView : MonoBehaviour, IHotfixable
{
	private GameObject _pnlComplete; // 0x18
	private GameObject _pnlIncomplete; // 0x20
	private GameObject _pnlReceived; // 0x28
	private Text _textDay; // 0x30
	private Text _textDesc; // 0x38
	private Color _colorDayComplete; // 0x40
	private Color _colorDayIncomplete; // 0x50
	private Color _colorDescComplete; // 0x60
	private Color _colorDescIncomplete; // 0x70
	private SimpleLayoutContent _rewardContainer; // 0x80
	private Single _itemCardScale; // 0x88
	private List`1 m_cachedRewardList; // 0x90
	private Adapter m_adapter; // 0x98
	private Boolean m_inited; // 0xa0
	private State m_cachedState; // 0xa4
	private String m_cachedRewardId; // 0xa8
	private Action`1 <onReceiveClicked>k__BackingField; // 0xb0
	private static DelegateBridge __Hotfix0_get_onReceiveClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onReceiveClicked; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_Render; // 0x18
	private static DelegateBridge __Hotfix0_OnReceiveClicked; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	private Action`1 onReceiveClicked { get; set; }

	// RVA: 0x25cc0f4 VA: 0x7594be40f4
	private Action`1 get_onReceiveClicked() { }
	// RVA: 0x25cbde4 VA: 0x7594be3de4
	public Void set_onReceiveClicked(Action`1 value) { }
	// RVA: 0x25cc15c VA: 0x7594be415c
	private Void _InitIfNot() { }
	// RVA: 0x25cbe68 VA: 0x7594be3e68
	public Void Render(SandboxV2ChallengeRewardViewModel viewModel) { }
	// RVA: 0x25cc2c0 VA: 0x7594be42c0
	public Void OnReceiveClicked() { }
	// RVA: 0x25cc378 VA: 0x7594be4378
	public Void .ctor() { }
}
```