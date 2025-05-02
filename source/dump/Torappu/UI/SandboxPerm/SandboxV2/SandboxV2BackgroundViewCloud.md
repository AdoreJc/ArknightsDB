# SandboxV2BackgroundViewCloud

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `RawImage _imageCloud`

- `Int32 _imageSize`

- `Boolean m_inited`

- `SeqNumChecker m_dungeonConstructChecker`

- `RenderTexture m_cloudMaskRT`

- `Material m_renderMat`

- `Material m_blurMat`


## Methods

- `Void _InitIfNot()`

- `Void OnDestroy()`

- `Void _RenderZoneMaskTexture(SandboxV2DungeonViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2BackgroundViewCloud : SandboxV2AbstractBackgroundView
{
	private const Int32 RT_WIDTH; // 0x0
	private const Int32 RT_HEIGHT; // 0x0
	private const String SHADER_NAME; // 0x0
	private RawImage _imageCloud; // 0x20
	private Int32 _imageSize; // 0x28
	private Boolean m_inited; // 0x2c
	private SeqNumChecker m_dungeonConstructChecker; // 0x30
	private HashSet`1 m_cachedUnlockedZone; // 0x40
	private RenderTexture m_cloudMaskRT; // 0x48
	private Material m_renderMat; // 0x50
	private Material m_blurMat; // 0x58
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0__GetUnlockedZone; // 0x18
	private static DelegateBridge __Hotfix0__RenderZoneMaskTexture; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x255addc VA: 0x7594b72ddc
	private Void _InitIfNot() { }
	// RVA: 0x255af30 VA: 0x7594b72f30
	private Void OnDestroy() { }
	// RVA: 0x255b060 VA: 0x7594b73060
	public override Void Render(SandboxV2DungeonViewModel viewModel) { }
	// RVA: 0x255b168 VA: 0x7594b73168
	private HashSet`1 _GetUnlockedZone(SandboxV2DungeonViewModel viewModel) { }
	// RVA: 0x255b384 VA: 0x7594b73384
	private Void _RenderZoneMaskTexture(SandboxV2DungeonViewModel viewModel) { }
	// RVA: 0x255b968 VA: 0x7594b73968
	public Void .ctor() { }
}
```