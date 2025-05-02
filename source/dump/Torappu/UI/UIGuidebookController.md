# UIGuidebookController

**Namespace:** `Torappu.UI`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIGuidebookController : SingletonMonoBehaviour`1, ISingletonNotAutoCreate
{
	private List`1 m_listeners; // 0x18
	private static DelegateBridge __Hotfix0_AddListener; // 0x0
	private static DelegateBridge __Hotfix0_RemoveListener; // 0x8
	private static DelegateBridge __Hotfix0_GuideOnlyNotifyAutoShow; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x217c650 VA: 0x7594794650
	public static Void AddListener(IGuidebookListener listener) { }
	// RVA: 0x217c7d0 VA: 0x75947947d0
	public static Void RemoveListener(IGuidebookListener listener) { }
	// RVA: 0x217c8d0 VA: 0x75947948d0
	public static Boolean GuideOnlyNotifyAutoShow(UIGuideTarget target, String subsignal) { }
	// RVA: 0x217cb54 VA: 0x7594794b54
	public Void .ctor() { }
}
```