# SandboxV2RiftTeamButtonItem

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `UIAnimationLocation _switchAnim`

- `Text _teamName`

- `GameObject _confirmHotspot`

- `Boolean m_hasInited`

- `UISwitchTween m_switchTween`

- `UIStateFinder m_stateFinder`

- `String m_cachedTeamId`


## Methods

- `Void Render(String, Boolean, String)`

- `Void _InitIfNot()`

- `Void OnTeamSelected()`

- `Void OnTeamConfirmed()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2RiftTeamButtonItem : MonoBehaviour, IHotfixable
{
	private UIAnimationLocation _switchAnim; // 0x18
	private Text _teamName; // 0x28
	private GameObject _confirmHotspot; // 0x30
	private Boolean m_hasInited; // 0x38
	private UISwitchTween m_switchTween; // 0x40
	private UIStateFinder m_stateFinder; // 0x48
	private String m_cachedTeamId; // 0x58
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_OnTeamSelected; // 0x10
	private static DelegateBridge __Hotfix0_OnTeamConfirmed; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x25ff7d8 VA: 0x7594c177d8
	public Void Render(String teamName, Boolean isSelected, String teamId) { }
	// RVA: 0x25ff8c8 VA: 0x7594c178c8
	private Void _InitIfNot() { }
	// RVA: 0x25ff9c4 VA: 0x7594c179c4
	public Void OnTeamSelected() { }
	// RVA: 0x25ffab4 VA: 0x7594c17ab4
	public Void OnTeamConfirmed() { }
	// RVA: 0x25ffb58 VA: 0x7594c17b58
	public Void .ctor() { }
}
```