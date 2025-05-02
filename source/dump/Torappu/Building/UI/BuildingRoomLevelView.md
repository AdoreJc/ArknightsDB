# BuildingRoomLevelView

**Namespace:** `Torappu.Building.UI`


## Fields

- `SimpleLayoutContent _levelContainer`

- `Color _mainColor`

- `Boolean _showMaxLevel`

- `Int32 m_maxLevel`

- `Int32 m_level`

- `Boolean m_isInited`

- `LevelAdapter m_adapter`

- `Boolean m_isColorOverrided`

- `Color m_overrideMainColor`

- `Boolean m_isIconOverrided`

- `Image m_overrideIcon`

- `Boolean m_isViewConfigDirty`


## Properties

- `Color overrideMainColor`

- `Color mainColor`

- `Image overrideIcon`

- `Image iconPrefab`

- `Int32 maxLevel`

- `Int32 level`


## Methods

- `Color get_overrideMainColor()`

- `Void set_overrideMainColor(Color)`

- `Color get_mainColor()`

- `Image get_overrideIcon()`

- `Void set_overrideIcon(Image)`

- `Image get_iconPrefab()`

- `Int32 get_maxLevel()`

- `Void set_maxLevel(Int32)`

- `Int32 get_level()`

- `Void set_level(Int32)`

- `Void SetLevel(Int32, Int32)`

- `Void _UpdateContent()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI
public class BuildingRoomLevelView : MonoBehaviour, IHotfixable
{
	private static readonly Color INACTIVE_COLOR; // 0x0
	private SimpleLayoutContent _levelContainer; // 0x18
	private Color _mainColor; // 0x20
	private Boolean _showMaxLevel; // 0x30
	private Int32 m_maxLevel; // 0x34
	private Int32 m_level; // 0x38
	private Boolean m_isInited; // 0x3c
	private LevelAdapter m_adapter; // 0x40
	private Boolean m_isColorOverrided; // 0x48
	private Color m_overrideMainColor; // 0x4c
	private Boolean m_isIconOverrided; // 0x5c
	private Image m_overrideIcon; // 0x60
	private Boolean m_isViewConfigDirty; // 0x68
	private static DelegateBridge __Hotfix0_get_overrideMainColor; // 0x10
	private static DelegateBridge __Hotfix0_set_overrideMainColor; // 0x18
	private static DelegateBridge __Hotfix0_get_mainColor; // 0x20
	private static DelegateBridge __Hotfix0_get_overrideIcon; // 0x28
	private static DelegateBridge __Hotfix0_set_overrideIcon; // 0x30
	private static DelegateBridge __Hotfix0_get_iconPrefab; // 0x38
	private static DelegateBridge __Hotfix0_get_maxLevel; // 0x40
	private static DelegateBridge __Hotfix0_set_maxLevel; // 0x48
	private static DelegateBridge __Hotfix0_get_level; // 0x50
	private static DelegateBridge __Hotfix0_set_level; // 0x58
	private static DelegateBridge __Hotfix0_SetLevel; // 0x60
	private static DelegateBridge __Hotfix0__UpdateContent; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70

	public Color overrideMainColor { get; set; }
	public Color mainColor { get; }
	public Image overrideIcon { get; set; }
	public Image iconPrefab { get; }
	public Int32 maxLevel { get; set; }
	public Int32 level { get; set; }

	// RVA: 0x3d41cb8 VA: 0x7596359cb8
	public Color get_overrideMainColor() { }
	// RVA: 0x3d41d30 VA: 0x7596359d30
	public Void set_overrideMainColor(Color value) { }
	// RVA: 0x3d41df0 VA: 0x7596359df0
	public Color get_mainColor() { }
	// RVA: 0x3d41e7c VA: 0x7596359e7c
	public Image get_overrideIcon() { }
	// RVA: 0x3d41ef4 VA: 0x7596359ef4
	public Void set_overrideIcon(Image value) { }
	// RVA: 0x3d41f98 VA: 0x7596359f98
	public Image get_iconPrefab() { }
	// RVA: 0x3d42050 VA: 0x759635a050
	public Int32 get_maxLevel() { }
	// RVA: 0x3d420c8 VA: 0x759635a0c8
	public Void set_maxLevel(Int32 value) { }
	// RVA: 0x3d422cc VA: 0x759635a2cc
	public Int32 get_level() { }
	// RVA: 0x3d42344 VA: 0x759635a344
	public Void set_level(Int32 value) { }
	// RVA: 0x3d33ffc VA: 0x759634bffc
	public Void SetLevel(Int32 level, Int32 maxLevel) { }
	// RVA: 0x3d42198 VA: 0x759635a198
	private Void _UpdateContent() { }
	// RVA: 0x3d424a0 VA: 0x759635a4a0
	public Void .ctor() { }
	// RVA: 0x3d42528 VA: 0x759635a528
	private static Void .cctor() { }
}
```