# SandboxV2NodePreviewEnemyView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `UIAtlasObject _dungeonAtlasObject`

- `GameObject _pnlEnemyIconNone`

- `GameObject _pnlEnemyIconNormal`

- `GameObject _pnlEnemyIconRush`

- `Button _btnEnemyDetail`

- `GameObject _pnlEnemyHp`

- `UIAtlasImage _pnlEnemyHpBkg`

- `UIAtlasImage _hpBar`

- `UIAtlasImage _hpBarBkg`

- `Text _textEnemyHpRatio`

- `Slider _sliderEnemyHpRatio`


## Methods

- `Void Render(SandboxV2DungeonNodeViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2NodePreviewEnemyView : MonoBehaviour, IHotfixable
{
	private const String REMAIN_ENEMY_FORMAT; // 0x0
	private UIAtlasObject _dungeonAtlasObject; // 0x18
	private GameObject _pnlEnemyIconNone; // 0x20
	private GameObject _pnlEnemyIconNormal; // 0x28
	private GameObject _pnlEnemyIconRush; // 0x30
	private Button _btnEnemyDetail; // 0x38
	private GameObject _pnlEnemyHp; // 0x40
	private UIAtlasImage _pnlEnemyHpBkg; // 0x48
	private UIAtlasImage _hpBar; // 0x50
	private UIAtlasImage _hpBarBkg; // 0x58
	private Text _textEnemyHpRatio; // 0x60
	private Slider _sliderEnemyHpRatio; // 0x68
	private EnemyHpBarConfig[] _hpBarConfigs; // 0x70
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x256d424 VA: 0x7594b85424
	public Void Render(SandboxV2DungeonNodeViewModel nodeViewModel) { }
	// RVA: 0x256d700 VA: 0x7594b85700
	public Void .ctor() { }
}
```