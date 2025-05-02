# Act20sideStageMapDecoViewPlugin

**Namespace:** `Torappu.Activity.Act20side`


## Fields

- `String m_cachedGroupId`

- `String m_cachedZoneId`


## Methods

- `Void OnCarClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act20side
public class Act20sideStageMapDecoViewPlugin : StageSideStoryMapDecroViewPlugin, IHotfixable
{
	private String m_cachedGroupId; // 0x18
	private String m_cachedZoneId; // 0x20
	private static DelegateBridge __Hotfix0_OnRefresh; // 0x0
	private static DelegateBridge __Hotfix0_OnCarClick; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x32efa48 VA: 0x7595907a48
	public override Void OnRefresh(StageSideStoryMapDecroViewPluginParams param) { }
	// RVA: 0x32efb4c VA: 0x7595907b4c
	public Void OnCarClick() { }
	// RVA: 0x32efc5c VA: 0x7595907c5c
	public Void .ctor() { }
}
```