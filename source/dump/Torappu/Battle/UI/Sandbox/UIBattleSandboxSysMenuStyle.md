# UIBattleSandboxSysMenuStyle

**Namespace:** `Torappu.Battle.UI.Sandbox`


## Fields

- `UIAtlasImage _mainTexture`

- `Image _confirmButtonImage`

- `Text _mainTitleText`

- `Text _mainContentText`

- `Text _extraText`

- `GameObject _enemyWidget`

- `Text _remainEnemyAmount`

- `UIAtlasObject _atlas`

- `String _defaultTitle`

- `String _emergencyTitle`

- `String _defaultTextureName`

- `String _emergencyTextureName`

- `Color _defaultButtonColor`

- `Color _emergencyButtonColor`

- `Color _defaultTextColor`

- `Color _emergencyTextColor`

- `String _defaultExtraText`

- `String _emergencyExtraText`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI.Sandbox
public class UIBattleSandboxSysMenuStyle : MonoBehaviour, IHotfixable
{
	private UIAtlasImage _mainTexture; // 0x18
	private Image _confirmButtonImage; // 0x20
	private Text _mainTitleText; // 0x28
	private Text _mainContentText; // 0x30
	private Text _extraText; // 0x38
	private GameObject _enemyWidget; // 0x40
	private Text _remainEnemyAmount; // 0x48
	private UIAtlasObject _atlas; // 0x50
	private String _defaultTitle; // 0x58
	private String _emergencyTitle; // 0x60
	private String _defaultTextureName; // 0x68
	private String _emergencyTextureName; // 0x70
	private Color _defaultButtonColor; // 0x78
	private Color _emergencyButtonColor; // 0x88
	private Color _defaultTextColor; // 0x98
	private Color _emergencyTextColor; // 0xa8
	private String _defaultExtraText; // 0xb8
	private String _emergencyExtraText; // 0xc0
	private String[] _mainContentList; // 0xc8
	private static DelegateBridge __Hotfix0_SetData; // 0x0
	private static DelegateBridge __Hotfix0_Hide; // 0x8
	private static DelegateBridge __Hotfix0_Show; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x209ce04 VA: 0x75946b4e04
	public virtual Void SetData(Boolean isEmergency, Boolean showEnemyInfo, SandboxBattleStyle style) { }
	// RVA: 0x209d2c4 VA: 0x75946b52c4
	public virtual Void Hide() { }
	// RVA: 0x209d33c VA: 0x75946b533c
	public virtual Void Show() { }
	// RVA: 0x209d3b4 VA: 0x75946b53b4
	public Void .ctor() { }
}
```