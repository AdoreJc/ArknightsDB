# SandboxV2RiftDifficultyItem

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Text _difficultyLevel`

- `TwoStateToggle _bgToggle`

- `GameObject _completedGo`

- `GameObject _newTrackGo`

- `GameObject _lockIconGo`

- `UIAnimationLocation _sizeAnim`

- `Color _canSelectLevelColor`

- `Color _canNotSelectLevelColor`

- `Boolean m_hasInited`

- `Int32 m_difficultyLevel`


## Methods

- `Void Render(Param, Single)`

- `Void _InitIfNot()`

- `Void OnDifficultyItemClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2RiftDifficultyItem : MonoBehaviour, IHotfixable
{
	private Text _difficultyLevel; // 0x18
	private TwoStateToggle _bgToggle; // 0x20
	private GameObject _completedGo; // 0x28
	private GameObject _newTrackGo; // 0x30
	private GameObject _lockIconGo; // 0x38
	private UIAnimationLocation _sizeAnim; // 0x40
	private Color _canSelectLevelColor; // 0x50
	private Color _canNotSelectLevelColor; // 0x60
	private Boolean m_hasInited; // 0x70
	private Action`1 m_onClicked; // 0x78
	private Int32 m_difficultyLevel; // 0x80
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_OnDifficultyItemClicked; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x25fbd10 VA: 0x7594c13d10
	public Void Render(Param param, Single selectIndex) { }
	// RVA: 0x25fbef0 VA: 0x7594c13ef0
	private Void _InitIfNot() { }
	// RVA: 0x25fbf80 VA: 0x7594c13f80
	public Void OnDifficultyItemClicked() { }
	// RVA: 0x25fc008 VA: 0x7594c14008
	public Void .ctor() { }
}
```