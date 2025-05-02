# StageZoneHomeSandboxPermToDoItem

**Namespace:** `Torappu.UI.Stage`


## Fields

- `RectTransform _container`

- `ZoneHomeSandboxPermTodoPluginBase m_itemView`

- `String m_cachedTopicId`


## Methods

- `Void _LoadSandboxPermPlugin(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageZoneHomeSandboxPermToDoItem : StageZoneHomeToDoItemPlugin, IHotfixable
{
	private RectTransform _container; // 0x28
	private ZoneHomeSandboxPermTodoPluginBase m_itemView; // 0x30
	private String m_cachedTopicId; // 0x38
	private static DelegateBridge __Hotfix0_OnDataUpdated; // 0x0
	private static DelegateBridge __Hotfix0_LoadMainSprite; // 0x8
	private static DelegateBridge __Hotfix0__LoadSandboxPermPlugin; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2f10510 VA: 0x7595528510
	protected override Void OnDataUpdated() { }
	// RVA: 0x2f108f8 VA: 0x75955288f8
	protected override Sprite LoadMainSprite() { }
	// RVA: 0x2f10704 VA: 0x7595528704
	private Void _LoadSandboxPermPlugin(String topicId) { }
	// RVA: 0x2f10ab4 VA: 0x7595528ab4
	public Void .ctor() { }
}
```