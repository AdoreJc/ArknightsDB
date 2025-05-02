# SpData 技力数据
## [SpType](./SpType.md)

## levelUpCost
## maxChargeTime
## spCost
## initSp
## increment
## m_incrementsForAllSpTypes

```C#
// Dll : Assembly-CSharp.dll
// Namespace: Torappu
[Serializable]
public class SpData : IHotfixable
{
	// Fields
	private static readonly SpData DEFAULT; // 0x0
	public SpType spType; // 0x10
	public ItemBundle[] levelUpCost; // 0x18
	public ObscuredInt maxChargeTime; // 0x20
	public ObscuredInt spCost; // 0x34
	public ObscuredInt initSp; // 0x48
	public ObscuredFloat increment; // 0x5c
	private Single[] m_incrementsForAllSpTypes; // 0x78
	private static DelegateBridge __Hotfix0_GetDefault; // 0x8
	private static DelegateBridge __Hotfix0_get_maxSp; // 0x10
	private static DelegateBridge __Hotfix0_get_inited; // 0x18
	private static DelegateBridge __Hotfix0_get_incrementsForAllSpTypes; // 0x20
	private static DelegateBridge __Hotfix0_Init; // 0x28
	private static DelegateBridge __Hotfix0_CreateFrom; // 0x30
	private static DelegateBridge __Hotfix0_Duplicate; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	// Properties
	public ObscuredInt maxSp { get; }
	public Boolean inited { get; }
	public Single[] incrementsForAllSpTypes { get; }

	// Methods
	// RVA: 0x34f4830 VA: 0x7595b0c830
	public static SpData GetDefault() { }
	// RVA: 0x34f4ac8 VA: 0x7595b0cac8
	public ObscuredInt get_maxSp() { }
	// RVA: 0x34f4be8 VA: 0x7595b0cbe8
	public Boolean get_inited() { }
	// RVA: 0x34f4c68 VA: 0x7595b0cc68
	public Single[] get_incrementsForAllSpTypes() { }
	// RVA: 0x34f48d4 VA: 0x7595b0c8d4
	public Void Init(Blackboard blackboard) { }
	// RVA: 0x34f4ce0 VA: 0x7595b0cce0
	public static SpData CreateFrom(ESpData eSpData, Blackboard blackboard) { }
	// RVA: 0x34f500c VA: 0x7595b0d00c
	public SpData Duplicate() { }
	// RVA: 0x34f4ea4 VA: 0x7595b0cea4
	public Void .ctor() { }
	// RVA: 0x34f50e4 VA: 0x7595b0d0e4
	private static Void .cctor() { }
}
```