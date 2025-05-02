# CarvingMainProcessModel

**Namespace:** `Torappu.UI.Carving`


## Fields

- `Int32 frameSeq`


## Properties

- `CarvingMainProcessFrameModel curFrame`

- `Int32 curBounce`


## Methods

- `CarvingMainProcessFrameModel get_curFrame()`

- `Int32 get_curBounce()`

- `Void LoadProcessFrame(Int32, Act35SideData, List`1)`

- `Boolean TryNextFrame()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Carving
public class CarvingMainProcessModel : IHotfixable
{
	public List`1 frameList; // 0x10
	public Int32 frameSeq; // 0x18
	private static DelegateBridge __Hotfix0_get_curFrame; // 0x0
	private static DelegateBridge __Hotfix0_get_curBounce; // 0x8
	private static DelegateBridge __Hotfix0_LoadProcessFrame; // 0x10
	private static DelegateBridge __Hotfix0_TryNextFrame; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public CarvingMainProcessFrameModel curFrame { get; }
	public Int32 curBounce { get; }

	// RVA: 0x2d996e4 VA: 0x75953b16e4
	public CarvingMainProcessFrameModel get_curFrame() { }
	// RVA: 0x2d9cb24 VA: 0x75953b4b24
	public Int32 get_curBounce() { }
	// RVA: 0x2d9cba0 VA: 0x75953b4ba0
	public Void LoadProcessFrame(Int32 beforeScore, Act35SideData actData, List`1 frames) { }
	// RVA: 0x2d9d528 VA: 0x75953b5528
	public Boolean TryNextFrame() { }
	// RVA: 0x2d9d5d0 VA: 0x75953b55d0
	public Void .ctor() { }
}
```