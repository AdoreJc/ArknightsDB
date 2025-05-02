# UIFlingGesture

**Namespace:** `Torappu.UI`


## Fields

- `Int32 m_frameCacheCnt`

- `Single m_curTime`


## Methods

- `Void BeginDrag(Vector2)`

- `Void Tick(Vector2, Single)`

- `Boolean EndDrag(out)`

- `Void _Reset()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIFlingGesture : IHotfixable
{
	private const Int32 DEFAULT_FRAME_CNT; // 0x0
	private Int32 m_frameCacheCnt; // 0x10
	private Queue`1 m_frames; // 0x18
	private Single m_curTime; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_BeginDrag; // 0x8
	private static DelegateBridge __Hotfix0_Tick; // 0x10
	private static DelegateBridge __Hotfix0_EndDrag; // 0x18
	private static DelegateBridge __Hotfix0__Reset; // 0x20


	// RVA: 0x21c4184 VA: 0x75947dc184
	public Void .ctor(Int32 frameCnt) { }
	// RVA: 0x21c4274 VA: 0x75947dc274
	public Void BeginDrag(Vector2 pressPos) { }
	// RVA: 0x21c43b8 VA: 0x75947dc3b8
	public Void Tick(Vector2 curPos, Single deltaTime) { }
	// RVA: 0x21c4514 VA: 0x75947dc514
	public Boolean EndDrag(out Vector2 flingSpeed) { }
	// RVA: 0x21c4330 VA: 0x75947dc330
	private Void _Reset() { }
}
```