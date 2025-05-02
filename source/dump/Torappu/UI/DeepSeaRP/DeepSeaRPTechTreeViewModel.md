# DeepSeaRPTechTreeViewModel

**Namespace:** `Torappu.UI.DeepSeaRP`


## Fields

- `Boolean isRetro`

- `String groupId`

- `SETTING_STATE settingState`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.DeepSeaRP
public class DeepSeaRPTechTreeViewModel : IHotfixable
{
	public Boolean isRetro; // 0x10
	public String groupId; // 0x18
	public List`1 nodeViewModelList; // 0x20
	public SETTING_STATE settingState; // 0x28
	private static DelegateBridge __Hotfix0__LoadDataList; // 0x0
	private static DelegateBridge __Hotfix0_LoadDataList; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x29e5e50 VA: 0x7594ffde50
	private static List`1 _LoadDataList(Act17sideData actData) { }
	// RVA: 0x29e47f0 VA: 0x7594ffc7f0
	public static List`1 LoadDataList(Boolean isRetro, String groupId) { }
	// RVA: 0x29e4780 VA: 0x7594ffc780
	public Void .ctor() { }
}
```