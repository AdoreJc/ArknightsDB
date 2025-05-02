# SandboxV2NodePreviewUpgradeView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Color _upgradedColor`

- `Color _notUpgradedColor`

- `GameObject _upgradeStroke`


## Methods

- `Void Render(SandboxV2DungeonNodeViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2NodePreviewUpgradeView : MonoBehaviour, IHotfixable
{
	private Color _upgradedColor; // 0x18
	private Color _notUpgradedColor; // 0x28
	private GameObject _upgradeStroke; // 0x38
	private UIAtlasImage[] _upgradeIcons; // 0x40
	private String[] _upgradeIds; // 0x48
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x256e9c4 VA: 0x7594b869c4
	public Void Render(SandboxV2DungeonNodeViewModel nodeViewModel) { }
	// RVA: 0x256ebf0 VA: 0x7594b86bf0
	public Void .ctor() { }
}
```