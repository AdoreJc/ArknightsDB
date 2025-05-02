# TileBasedColorController

**Namespace:** `Torappu.Battle`


## Fields

- `Texture2D m_colorTexture`

- `Vector4 m_mapParams`

- `Boolean m_colorDirty`


## Properties

- `Int32 m_width`

- `Int32 m_height`


## Methods

- `Int32 get_m_width()`

- `Int32 get_m_height()`

- `Void Init(Map)`

- `Void SetColor(GridPosition, Color)`

- `Texture2D _CreateTextureInternal(Int32, Int32, Color[])`

- `Void _UpdateTexture()`

- `Boolean _CheckGridPosValid(GridPosition)`

- `Void LateUpdate()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class TileBasedColorController : SingletonMonoBehaviour`1
{
	private const String COLOR_TEXTURE_NAME; // 0x0
	private Texture2D m_colorTexture; // 0x18
	private Vector4 m_mapParams; // 0x20
	private Color[] m_colors; // 0x30
	private Boolean m_colorDirty; // 0x38
	private static DelegateBridge __Hotfix0_get_m_width; // 0x0
	private static DelegateBridge __Hotfix0_get_m_height; // 0x8
	private static DelegateBridge __Hotfix0_Init; // 0x10
	private static DelegateBridge __Hotfix0_SetColor; // 0x18
	private static DelegateBridge __Hotfix0__CreateTextureInternal; // 0x20
	private static DelegateBridge __Hotfix0__UpdateTexture; // 0x28
	private static DelegateBridge __Hotfix0__CheckGridPosValid; // 0x30
	private static DelegateBridge __Hotfix0_LateUpdate; // 0x38
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	private Int32 m_width { get; }
	private Int32 m_height { get; }

	// RVA: 0x409a6f0 VA: 0x75966b26f0
	private Int32 get_m_width() { }
	// RVA: 0x409a7c8 VA: 0x75966b27c8
	private Int32 get_m_height() { }
	// RVA: 0x409a8a0 VA: 0x75966b28a0
	public Void Init(Map map) { }
	// RVA: 0x409ab90 VA: 0x75966b2b90
	public Void SetColor(GridPosition gridPos, Color color) { }
	// RVA: 0x409aa58 VA: 0x75966b2a58
	private Texture2D _CreateTextureInternal(Int32 width, Int32 height, Color[] colors) { }
	// RVA: 0x409ae0c VA: 0x75966b2e0c
	private Void _UpdateTexture() { }
	// RVA: 0x409ad58 VA: 0x75966b2d58
	private Boolean _CheckGridPosValid(GridPosition gridPos) { }
	// RVA: 0x409ae9c VA: 0x75966b2e9c
	private Void LateUpdate() { }
	// RVA: 0x409af18 VA: 0x75966b2f18
	protected override Void OnDestroy() { }
	// RVA: 0x409b054 VA: 0x75966b3054
	public Void .ctor() { }
}
```