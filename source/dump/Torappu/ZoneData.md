# ZoneData

**Namespace:** `Torappu`


## Fields

- `String zoneID`

- `Int32 zoneIndex`

- `ZoneType type`

- `String zoneNameFirst`

- `String zoneNameSecond`

- `String zoneNameTitleCurrent`

- `String zoneNameTitleUnCurrent`

- `String zoneNameTitleEx`

- `String zoneNameThird`

- `String lockedText`

- `String antiSpoilerId`

- `Boolean canPreview`

- `Boolean hasAdditionalPanel`

- `String sixStarMilestoneGroupId`

- `String bindMainlineZoneId`

- `String bindMainlineRetroZoneId`


## Methods

- `Boolean ShouldSerializebindMainlineZoneId()`

- `Boolean ShouldSerializebindMainlineRetroZoneId()`

- `Boolean ShouldSerializesixStarMilestoneGroupId()`

- `Boolean ShouldSerializehasAdditionalPanel()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class ZoneData
{
	public String zoneID; // 0x10
	public Int32 zoneIndex; // 0x18
	public ZoneType type; // 0x1c
	public String zoneNameFirst; // 0x20
	public String zoneNameSecond; // 0x28
	public String zoneNameTitleCurrent; // 0x30
	public String zoneNameTitleUnCurrent; // 0x38
	public String zoneNameTitleEx; // 0x40
	public String zoneNameThird; // 0x48
	public String lockedText; // 0x50
	public String antiSpoilerId; // 0x58
	public Boolean canPreview; // 0x60
	public Boolean hasAdditionalPanel; // 0x61
	public String sixStarMilestoneGroupId; // 0x68
	public String bindMainlineZoneId; // 0x70
	public String bindMainlineRetroZoneId; // 0x78


	// RVA: 0x34f8ebc VA: 0x7595b10ebc
	public Boolean ShouldSerializebindMainlineZoneId() { }
	// RVA: 0x34f8edc VA: 0x7595b10edc
	public Boolean ShouldSerializebindMainlineRetroZoneId() { }
	// RVA: 0x34f8efc VA: 0x7595b10efc
	public Boolean ShouldSerializesixStarMilestoneGroupId() { }
	// RVA: 0x34f8f1c VA: 0x7595b10f1c
	public Boolean ShouldSerializehasAdditionalPanel() { }
	// RVA: 0x34f8f24 VA: 0x7595b10f24
	public virtual Boolean ShouldSerializeantiSpoilerId() { }
	// RVA: 0x34f8f44 VA: 0x7595b10f44
	public Void .ctor() { }
}
```