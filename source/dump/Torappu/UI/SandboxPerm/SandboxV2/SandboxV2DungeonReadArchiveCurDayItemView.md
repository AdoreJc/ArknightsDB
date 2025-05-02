# SandboxV2DungeonReadArchiveCurDayItemView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Text _txtDayTitle`

- `Text _txtDayCount`

- `SimpleLayoutContent _apListContent`

- `Int32 m_day`

- `Boolean m_isInited`

- `SandboxV2DungeonReadArchiveCurDayInfoItemData m_cachedData`

- `ApItemListAdapter m_adapter`


## Methods

- `Void Render(SandboxV2DungeonReadArchiveCurDayInfoItemData)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonReadArchiveCurDayItemView : MonoBehaviour, IHotfixable
{
	private Text _txtDayTitle; // 0x18
	private Text _txtDayCount; // 0x20
	private SimpleLayoutContent _apListContent; // 0x28
	private Int32 m_day; // 0x30
	private Boolean m_isInited; // 0x34
	private SandboxV2DungeonReadArchiveCurDayInfoItemData m_cachedData; // 0x38
	private ApItemListAdapter m_adapter; // 0x50
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2529d7c VA: 0x7594b41d7c
	public Void Render(SandboxV2DungeonReadArchiveCurDayInfoItemData itemData) { }
	// RVA: 0x2529e98 VA: 0x7594b41e98
	private Void _InitIfNot() { }
	// RVA: 0x252a04c VA: 0x7594b4204c
	public Void .ctor() { }
}
```