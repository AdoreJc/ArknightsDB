# DeepSeaRPBattlePreviewConfigController

**Namespace:** `Torappu.UI.DeepSeaRP`


## Fields

- `TwoStateToggle _btnHard`

- `GameObject _btnHardLocked`

- `TwoStateToggle _btnPractice`

- `TwoStateToggle _btnAutoBattle`

- `GameObject _btnAutoBattleLocked`

- `GameObject _btnReplayStory`

- `StagePreviewApStatusBinder _apStatusView`

- `Boolean m_isInited`

- `Boolean m_isAutoBattleUnlocked`

- `UIPage m_page`


## Properties

- `UIPage page`


## Methods

- `Void OnAutoBattleLocked()`

- `UIPage get_page()`

- `Void Setup(UIPage)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.DeepSeaRP
public class DeepSeaRPBattlePreviewConfigController : DataBinder`1
{
	private TwoStateToggle _btnHard; // 0x20
	private GameObject _btnHardLocked; // 0x28
	private TwoStateToggle _btnPractice; // 0x30
	private TwoStateToggle _btnAutoBattle; // 0x38
	private GameObject _btnAutoBattleLocked; // 0x40
	private GameObject _btnReplayStory; // 0x48
	private StagePreviewApStatusBinder _apStatusView; // 0x50
	private Boolean m_isInited; // 0x58
	private Boolean m_isAutoBattleUnlocked; // 0x59
	private UIPage m_page; // 0x60
	private static DelegateBridge __Hotfix0_OnAutoBattleLocked; // 0x0
	private static DelegateBridge __Hotfix0_get_page; // 0x8
	private static DelegateBridge __Hotfix0_Setup; // 0x10
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	protected UIPage page { get; }

	// RVA: 0x29bc8b0 VA: 0x7594fd48b0
	public Void OnAutoBattleLocked() { }
	// RVA: 0x29bc948 VA: 0x7594fd4948
	protected UIPage get_page() { }
	// RVA: 0x29bc9b0 VA: 0x7594fd49b0
	public Void Setup(UIPage page) { }
	// RVA: 0x29bca34 VA: 0x7594fd4a34
	public override Void OnValueChanged(DeepSeaRPBattleNodeConfigProperty property) { }
	// RVA: 0x29bcc54 VA: 0x7594fd4c54
	private Void _InitIfNot() { }
	// RVA: 0x29bcd60 VA: 0x7594fd4d60
	public Void .ctor() { }
}
```