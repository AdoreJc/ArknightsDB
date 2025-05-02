# Tracking

**Namespace:** ` `


## Methods

- `Void Awake()`

- `Void init(String, String)`

- `Void register(String)`

- `Void login(String)`

- `Void setryzf(String, String, String, Single)`

- `Void setDD(String, String, Single)`

- `Void setEvent(String)`

- `Void setTrackViewDuration(String, Int64)`

- `Void setTrackAdShow(String, String)`

- `Void setTrackAdClick(String, String)`

- `Void setTrackAppDuration(Int64)`

- `String getDeviceId()`

- `Void setPrintLog(Boolean)`

- `Void setU8data(Int32, String)`

- `String getU8data()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class Tracking : MonoBehaviour
{
	private static Tracking _instance; // 0x0
	private static Dictionary`2 data_api; // 0x8
	private static Dictionary`2 data; // 0x10

	public static Tracking Instance { get; }

	// RVA: 0x1b25b84 VA: 0x759413db84
	public static Tracking get_Instance() { }
	// RVA: 0x1b25e38 VA: 0x759413de38
	private Void Awake() { }
	// RVA: 0x1b25e90 VA: 0x759413de90
	public Void init(String appKey, String channelId) { }
	// RVA: 0x1b26160 VA: 0x759413e160
	public Void register(String account) { }
	// RVA: 0x1b2625c VA: 0x759413e25c
	public Void login(String account) { }
	// RVA: 0x1b26358 VA: 0x759413e358
	public Void setryzf(String ryTID, String ryzfType, String hbType, Single hbAmount) { }
	// RVA: 0x1b26538 VA: 0x759413e538
	public Void setDD(String ryTID, String hbType, Single hbAmount) { }
	// RVA: 0x1b266e8 VA: 0x759413e6e8
	public Void setEvent(String eventName) { }
	// RVA: 0x1b267e4 VA: 0x759413e7e4
	public Void setTrackViewDuration(String pageID, Int64 duration) { }
	// RVA: 0x1b26954 VA: 0x759413e954
	public Void setTrackAdShow(String adPlatform, String adId) { }
	// RVA: 0x1b26a90 VA: 0x759413ea90
	public Void setTrackAdClick(String adPlatform, String adId) { }
	// RVA: 0x1b26bcc VA: 0x759413ebcc
	public Void setTrackAppDuration(Int64 duration) { }
	// RVA: 0x1b26cfc VA: 0x759413ecfc
	public String getDeviceId() { }
	// RVA: 0x1b26d58 VA: 0x759413ed58
	public Void setPrintLog(Boolean print) { }
	// RVA: 0x1b25fcc VA: 0x759413dfcc
	private Void setU8data(Int32 key, String json) { }
	// RVA: 0x1b26d00 VA: 0x759413ed00
	private String getU8data() { }
	// RVA: 0x1b26e94 VA: 0x759413ee94
	public Void .ctor() { }
}
```