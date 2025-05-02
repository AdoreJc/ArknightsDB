# SandboxV2BasementUpgradePreviewGroupView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Image _groupIcon`

- `SimpleLayoutContent _itemContent`

- `Text _groupTitle`

- `UpgradePreviewItemAdapter m_adapter`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void Render(ILoadAsset, SandboxV2BasementUpgradePreviewGroupViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2BasementUpgradePreviewGroupView : MonoBehaviour, IHotfixable
{
	private Image _groupIcon; // 0x18
	private SimpleLayoutContent _itemContent; // 0x20
	private Text _groupTitle; // 0x28
	private UpgradePreviewItemAdapter m_adapter; // 0x30
	private Boolean m_isInited; // 0x38
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x250e8cc VA: 0x7594b268cc
	private Void _InitIfNot() { }
	// RVA: 0x250ea08 VA: 0x7594b26a08
	public Void Render(ILoadAsset assetLoader, SandboxV2BasementUpgradePreviewGroupViewModel groupViewModel) { }
	// RVA: 0x250ebb8 VA: 0x7594b26bb8
	public Void .ctor() { }
}
```