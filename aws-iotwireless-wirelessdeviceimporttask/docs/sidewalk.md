# AWS::IoTWireless::WirelessDeviceImportTask Sidewalk

sidewalk contain file for created device and role

## Syntax

To declare this entity in your AWS CloudFormation template, use the following syntax:

### JSON

<pre>
{
    "<a href="#sidewalkmanufacturingsn" title="SidewalkManufacturingSn">SidewalkManufacturingSn</a>" : <i>String</i>,
    "<a href="#devicecreationfile" title="DeviceCreationFile">DeviceCreationFile</a>" : <i>String</i>,
    "<a href="#role" title="Role">Role</a>" : <i>String</i>
}
</pre>

### YAML

<pre>
<a href="#sidewalkmanufacturingsn" title="SidewalkManufacturingSn">SidewalkManufacturingSn</a>: <i>String</i>
<a href="#devicecreationfile" title="DeviceCreationFile">DeviceCreationFile</a>: <i>String</i>
<a href="#role" title="Role">Role</a>: <i>String</i>
</pre>

## Properties

#### SidewalkManufacturingSn

_Required_: Yes

_Type_: String

_Maximum_: <code>64</code>

_Update requires_: [No interruption](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-update-behaviors.html#update-no-interrupt)

#### DeviceCreationFile

_Required_: Yes

_Type_: String

_Maximum_: <code>1024</code>

_Update requires_: [No interruption](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-update-behaviors.html#update-no-interrupt)

#### Role

sidewalk role

_Required_: Yes

_Type_: String

_Maximum_: <code>2048</code>

_Update requires_: [No interruption](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-update-behaviors.html#update-no-interrupt)

