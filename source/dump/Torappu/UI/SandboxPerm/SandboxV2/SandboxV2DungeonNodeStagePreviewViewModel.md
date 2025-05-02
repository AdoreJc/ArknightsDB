# SandboxV2DungeonNodeStagePreviewViewModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `String m_topicId`

- `String m_stageId`


## Properties

- `String topicId`

- `String stageId`


## Methods

- `String get_topicId()`

- `String get_stageId()`

- `Void LoadData(String, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonNodeStagePreviewViewModel : IHotfixable
{
	private String m_topicId; // 0x10
	private String m_stageId; // 0x18
	private static DelegateBridge __Hotfix0_get_topicId; // 0x0
	private static DelegateBridge __Hotfix0_get_stageId; // 0x8
	private static DelegateBridge __Hotfix0_LoadData; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public String topicId { get; }
	public String stageId { get; }

	// RVA: 0x25b6bf8 VA: 0x7594bcebf8
	public String get_topicId() { }
	// RVA: 0x25b6c60 VA: 0x7594bcec60
	public String get_stageId() { }
	// RVA: 0x25b6cc8 VA: 0x7594bcecc8
	public Void LoadData(String topicId, String stageId) { }
	// RVA: 0x25b6d64 VA: 0x7594bced64
	public Void .ctor() { }
}
```