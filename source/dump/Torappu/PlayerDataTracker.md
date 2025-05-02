# PlayerDataTracker

**Namespace:** `Torappu`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class PlayerDataTracker : SingletonInScene`1
{
	private List`1 m_listeners; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_Register; // 0x8
	private static DelegateBridge __Hotfix0_Unregister; // 0x10
	private static DelegateBridge __Hotfix0_PlayerDataOnlyNotifyDataChanged; // 0x18


	// RVA: 0x3104014 VA: 0x759571c014
	private Void .ctor() { }
	// RVA: 0x31040f8 VA: 0x759571c0f8
	public static Void Register(IPlayerDataListener listener) { }
	// RVA: 0x31042d4 VA: 0x759571c2d4
	public static Void Unregister(IPlayerDataListener listener) { }
	// RVA: 0x3104380 VA: 0x759571c380
	public static Void PlayerDataOnlyNotifyDataChanged(PlayerDataModel prevData, PlayerDataDelta delta) { }
}
```