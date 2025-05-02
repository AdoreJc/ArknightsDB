# SandboxV2NodePreviewDropNpcView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `GameObject _dropPanel`

- `GameObject _emptyDropPanel`

- `GameObject _normalDropPanel`

- `GameObject _npcPanel`

- `SimpleLayoutContent _dropContent`

- `GameObject _noDropPanel`

- `Single _dropItemScale`

- `SandboxV2NodePreviewNpcLoopAdapter _npcLoopAdapter`

- `LoopHorizontalScrollRect _npcScrollRect`

- `Button _dropDetailButton`

- `Boolean m_hasInited`

- `DropAdapter m_dropAdapter`


## Methods

- `Void Render(SandboxV2DungeonNodeViewModel)`

- `Void _InitIfNot()`

- `Void _UpdateDropDetail(SandboxV2DungeonNodeViewModel)`

- `Void _SortNpc()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2NodePreviewDropNpcView : MonoBehaviour, IHotfixable
{
	private const Int32 PREVIEW_DROP_ITEM_COUNT; // 0x0
	private GameObject _dropPanel; // 0x18
	private GameObject _emptyDropPanel; // 0x20
	private GameObject _normalDropPanel; // 0x28
	private GameObject _npcPanel; // 0x30
	private SimpleLayoutContent _dropContent; // 0x38
	private GameObject _noDropPanel; // 0x40
	private Single _dropItemScale; // 0x48
	private SandboxV2NodePreviewNpcLoopAdapter _npcLoopAdapter; // 0x50
	private LoopHorizontalScrollRect _npcScrollRect; // 0x58
	private Button _dropDetailButton; // 0x60
	private Boolean m_hasInited; // 0x68
	private DropAdapter m_dropAdapter; // 0x70
	private List`1 m_cachedDropDetailList; // 0x78
	private readonly List`1 m_duplicatedNpcList; // 0x80
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__UpdateDropDetail; // 0x10
	private static DelegateBridge __Hotfix0__SortNpc; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x256c6f4 VA: 0x7594b846f4
	public Void Render(SandboxV2DungeonNodeViewModel nodeViewModel) { }
	// RVA: 0x256c9cc VA: 0x7594b849cc
	private Void _InitIfNot() { }
	// RVA: 0x256cac8 VA: 0x7594b84ac8
	private Void _UpdateDropDetail(SandboxV2DungeonNodeViewModel nodeViewModel) { }
	// RVA: 0x256cc84 VA: 0x7594b84c84
	private Void _SortNpc() { }
	// RVA: 0x256cf64 VA: 0x7594b84f64
	public Void .ctor() { }
}
```