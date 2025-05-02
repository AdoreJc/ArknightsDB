# SandboxV2NodePreviewStartBattleView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `UIAtlasObject _dungeonAtlasObject`

- `UIAtlasImage _imgStartBattle`

- `Color _colorStartBattleLocked`

- `Color _colorStartBattleUnlocked`

- `GameObject _pnlAp`

- `Text _textAp`

- `Text _textStartBattle`

- `GameObject _pnlUnlocked`

- `GameObject _pnlLocked`

- `Text _textLockedTip`


## Methods

- `Void Render(SandboxV2DungeonNodeViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2NodePreviewStartBattleView : MonoBehaviour, IHotfixable
{
	private const String AP_COST_FORMAT; // 0x0
	private UIAtlasObject _dungeonAtlasObject; // 0x18
	private UIAtlasImage _imgStartBattle; // 0x20
	private Color _colorStartBattleLocked; // 0x28
	private Color _colorStartBattleUnlocked; // 0x38
	private String[] _startBattleSpriteNames; // 0x48
	private GameObject _pnlAp; // 0x50
	private Text _textAp; // 0x58
	private Text _textStartBattle; // 0x60
	private GameObject _pnlUnlocked; // 0x68
	private GameObject _pnlLocked; // 0x70
	private Text _textLockedTip; // 0x78
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x256e2d8 VA: 0x7594b862d8
	public Void Render(SandboxV2DungeonNodeViewModel nodeViewModel) { }
	// RVA: 0x256e664 VA: 0x7594b86664
	public Void .ctor() { }
}
```