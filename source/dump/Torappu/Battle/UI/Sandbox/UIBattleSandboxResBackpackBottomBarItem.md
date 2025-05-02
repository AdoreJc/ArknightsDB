# UIBattleSandboxResBackpackBottomBarItem

**Namespace:** `Torappu.Battle.UI.Sandbox`


## Fields

- `Image _itemIcon`

- `Text _totalCountText`

- `Color _colorWater`

- `Color _colorNormal`

- `Int32 m_countTotal`

- `SandboxGameMode m_gameMode`


## Properties

- `SandboxGameMode sandboxGameMode`


## Methods

- `SandboxGameMode get_sandboxGameMode()`

- `Void SetData(String)`

- `Sprite _LoadItemIcon(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI.Sandbox
public class UIBattleSandboxResBackpackBottomBarItem : MonoBehaviour, IHotfixable
{
	private Image _itemIcon; // 0x18
	private Text _totalCountText; // 0x20
	private Color _colorWater; // 0x28
	private Color _colorNormal; // 0x38
	private Int32 m_countTotal; // 0x48
	private SandboxGameMode m_gameMode; // 0x50
	private static DelegateBridge __Hotfix0_get_sandboxGameMode; // 0x0
	private static DelegateBridge __Hotfix0_SetData; // 0x8
	private static DelegateBridge __Hotfix0__LoadItemIcon; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	private SandboxGameMode sandboxGameMode { get; }

	// RVA: 0x20c29ec VA: 0x75946da9ec
	private SandboxGameMode get_sandboxGameMode() { }
	// RVA: 0x20c2a9c VA: 0x75946daa9c
	public Void SetData(String itemId) { }
	// RVA: 0x20c2c74 VA: 0x75946dac74
	private Sprite _LoadItemIcon(String itemId) { }
	// RVA: 0x20c2d84 VA: 0x75946dad84
	public Void .ctor() { }
}
```