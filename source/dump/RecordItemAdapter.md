# RecordItemAdapter

**Namespace:** ` `


## Fields

- `ArchiveChatRecordListDataBinder m_closure`

- `ChatItemModel chatItemModel`


## Methods

- `String _TryLoadTextAssets(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class RecordItemAdapter : SimpleLayoutAdapter
{
	private ArchiveChatRecordListDataBinder m_closure; // 0x20
	public ChatItemModel chatItemModel; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_get_count; // 0x8
	private static DelegateBridge __Hotfix0_RenderView; // 0x10
	private static DelegateBridge __Hotfix0__TryLoadTextAssets; // 0x18

	public override Int32 count { get; }

	// RVA: 0x3047440 VA: 0x759565f440
	public Void .ctor(ArchiveChatRecordListDataBinder closure) { }
	// RVA: 0x3047970 VA: 0x759565f970
	public override Int32 get_count() { }
	// RVA: 0x30479e8 VA: 0x759565f9e8
	public override GameObject RenderView(Int32 position, GameObject prefab, Transform parent) { }
	// RVA: 0x3047c34 VA: 0x759565fc34
	private String _TryLoadTextAssets(String textId) { }
}
```