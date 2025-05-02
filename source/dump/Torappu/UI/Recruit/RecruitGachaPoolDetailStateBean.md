# RecruitGachaPoolDetailStateBean

**Namespace:** `Torappu.UI.Recruit`


## Fields

- `String poolId`

- `GachaDetailExtraInput extraInput`

- `Boolean needCleanCache`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Recruit
public class RecruitGachaPoolDetailStateBean : MonoBehaviour, IStateBean, IHotfixable
{
	public String poolId; // 0x18
	public GachaDetailExtraInput extraInput; // 0x20
	public Boolean needCleanCache; // 0x2c
	public Dictionary`2 cacheDetailDataMap; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0


	// RVA: 0x26fe0ac VA: 0x7594d160ac
	public Void .ctor() { }
}
```