# RuntimeAtlasManager

**Namespace:** `Torappu.UI`


## Fields

- `Boolean _enableRuntimeAtlas`

- `CommandBuffer m_commandBuffer`

- `GraphicsFormat m_atlasSheetFormat`


## Methods

- `Void LateUpdate()`

- `Void _AddUIImageToManager(Image)`

- `Void _ReProcessInsertForUIImage(Image)`

- `Void _RemoveUIImageFromManager(Image)`

- `Void _AddUIImageToManagerOnInstantiate(Image)`

- `Boolean _IsRuntimeAtlasCompatible(Image, out)`

- `Void _ProcessInsertQueue()`

- `Void _ProcessRemoveQueue()`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : Torappu.UI
public class RuntimeAtlasManager : SingletonMonoBehaviour`1
{
	public const Int32 ATLAS_PAGE_WIDTH; // 0x0
	public const Int32 ATLAS_PAGE_HEIGHT; // 0x0
	public const Int32 IMAGE_USING_ATLAS_MAX_SIZE; // 0x0
	public const Int32 PANEL_LEVEL_COUNT; // 0x0
	public const Int32 MAX_ATLAS_PER_PANEL_LEVEL; // 0x0
	public const Int32 PROCESS_COUNT_PER_FRAME; // 0x0
	public const GraphicsFormat ATLAS_PAGE_FORMAT; // 0x0
	private Boolean _enableRuntimeAtlas; // 0x18
	private Dictionary`2 m_imageDict; // 0x20
	private AtlasSheet[,] m_atlasSheetPool; // 0x28
	private Queue`1 m_insertQueue; // 0x30
	private Queue`1 m_freeQueue; // 0x38
	private CommandBuffer m_commandBuffer; // 0x40
	private GraphicsFormat m_atlasSheetFormat; // 0x48
	private static Boolean <enableRuntimeAtlasFromScript>k__BackingField; // 0x0
	private static __XLua_Gen_Delegate5 __Hotfix0_get_releaseImageSpriteAfterInsert; // 0x8
	private static __XLua_Gen_Delegate5 __Hotfix0_get_enableRuntimeAtlas; // 0x10
	private static __XLua_Gen_Delegate5 __Hotfix0_get_enableRuntimeAtlasFromScript; // 0x18
	private static __XLua_Gen_Delegate98 __Hotfix0_set_enableRuntimeAtlasFromScript; // 0x20
	private static __XLua_Gen_Delegate1 __Hotfix0_OnInit; // 0x28
	private static __XLua_Gen_Delegate1 __Hotfix0_AddUIImageToManager; // 0x30
	private static __XLua_Gen_Delegate1 __Hotfix0_ReProcessInsertForUIImage; // 0x38
	private static __XLua_Gen_Delegate1 __Hotfix0_RemoveUIImageFromManager; // 0x40
	private static __XLua_Gen_Delegate1 __Hotfix0_AddUIImageToManagerOnInstantiate; // 0x48
	private static __XLua_Gen_Delegate1 __Hotfix0_LateUpdate; // 0x50
	private static __XLua_Gen_Delegate0 __Hotfix0__AddUIImageToManager; // 0x58
	private static __XLua_Gen_Delegate0 __Hotfix0__ReProcessInsertForUIImage; // 0x60
	private static __XLua_Gen_Delegate0 __Hotfix0__RemoveUIImageFromManager; // 0x68
	private static __XLua_Gen_Delegate0 __Hotfix0__AddUIImageToManagerOnInstantiate; // 0x70
	private static __XLua_Gen_Delegate99 __Hotfix0__IsRuntimeAtlasCompatible; // 0x78
	private static __XLua_Gen_Delegate1 __Hotfix0__ProcessInsertQueue; // 0x80
	private static __XLua_Gen_Delegate1 __Hotfix0__ProcessRemoveQueue; // 0x88
	private static __XLua_Gen_Delegate1 _c__Hotfix0_ctor; // 0x90

	public static Boolean releaseImageSpriteAfterInsert { get; }
	public static Boolean enableRuntimeAtlas { get; }
	public static Boolean enableRuntimeAtlasFromScript { get; set; }

	// RVA: 0x6786a58 VA: 0x7598d9ea58
	public static Boolean get_releaseImageSpriteAfterInsert() { }
	// RVA: 0x6786ad0 VA: 0x7598d9ead0
	public static Boolean get_enableRuntimeAtlas() { }
	// RVA: 0x6786bb0 VA: 0x7598d9ebb0
	public static Boolean get_enableRuntimeAtlasFromScript() { }
	// RVA: 0x6786c3c VA: 0x7598d9ec3c
	public static Void set_enableRuntimeAtlasFromScript(Boolean value) { }
	// RVA: 0x6786cd4 VA: 0x7598d9ecd4
	protected override Void OnInit() { }
	// RVA: 0x6786f6c VA: 0x7598d9ef6c
	public static Void AddUIImageToManager(Image image) { }
	// RVA: 0x6787180 VA: 0x7598d9f180
	public static Void ReProcessInsertForUIImage(Image image) { }
	// RVA: 0x678741c VA: 0x7598d9f41c
	public static Void RemoveUIImageFromManager(Image image) { }
	// RVA: 0x67876ac VA: 0x7598d9f6ac
	public static Void AddUIImageToManagerOnInstantiate(Image image) { }
	// RVA: 0x6787a04 VA: 0x7598d9fa04
	protected Void LateUpdate() { }
	// RVA: 0x6787040 VA: 0x7598d9f040
	private Void _AddUIImageToManager(Image image) { }
	// RVA: 0x6787254 VA: 0x7598d9f254
	private Void _ReProcessInsertForUIImage(Image image) { }
	// RVA: 0x67874f0 VA: 0x7598d9f4f0
	private Void _RemoveUIImageFromManager(Image image) { }
	// RVA: 0x6787780 VA: 0x7598d9f780
	private Void _AddUIImageToManagerOnInstantiate(Image image) { }
	// RVA: 0x6788518 VA: 0x7598da0518
	private Boolean _IsRuntimeAtlasCompatible(Image image, out ProcessFailureCause failureCause) { }
	// RVA: 0x6787dd8 VA: 0x7598d9fdd8
	private Void _ProcessInsertQueue() { }
	// RVA: 0x6787af0 VA: 0x7598d9faf0
	private Void _ProcessRemoveQueue() { }
	// RVA: 0x6788be8 VA: 0x7598da0be8
	public Void .ctor() { }
	// RVA: 0x6788c98 VA: 0x7598da0c98
	private static Void .cctor() { }
}
```