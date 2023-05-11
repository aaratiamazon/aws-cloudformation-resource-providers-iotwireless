# AWS::IoTWireless::WirelessDeviceImportTask

Wireless Device Import Tasks

## Syntax

To declare this entity in your AWS CloudFormation template, use the following syntax:

### JSON

<pre>
{
    "Type" : "AWS::IoTWireless::WirelessDeviceImportTask",
    "Properties" : {
        "<a href="#destinationname" title="DestinationName">DestinationName</a>" : <i>String</i>,
        "<a href="#sidewalk" title="Sidewalk">Sidewalk</a>" : <i><a href="sidewalk.md">Sidewalk</a></i>,
        "<a href="#tags" title="Tags">Tags</a>" : <i>[ <a href="tag.md">Tag</a>, ... ]</i>
    }
}
</pre>

### YAML

<pre>
Type: AWS::IoTWireless::WirelessDeviceImportTask
Properties:
    <a href="#destinationname" title="DestinationName">DestinationName</a>: <i>String</i>
    <a href="#sidewalk" title="Sidewalk">Sidewalk</a>: <i><a href="sidewalk.md">Sidewalk</a></i>
    <a href="#tags" title="Tags">Tags</a>: <i>
      - <a href="tag.md">Tag</a></i>
</pre>

## Properties

#### DestinationName

Destination Name for import task

_Required_: Yes

_Type_: String

_Maximum_: <code>128</code>

_Pattern_: <code>[a-zA-Z0-9-_]+</code>

_Update requires_: [No interruption](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-update-behaviors.html#update-no-interrupt)

#### Sidewalk

sidewalk contain file for created device and role

_Required_: Yes

_Type_: <a href="sidewalk.md">Sidewalk</a>

_Update requires_: [No interruption](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-update-behaviors.html#update-no-interrupt)

#### Tags

An array of key-value pairs to apply to this resource.

_Required_: No

_Type_: List of <a href="tag.md">Tag</a>

_Update requires_: [No interruption](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-update-behaviors.html#update-no-interrupt)

## Return Values

### Ref

When you pass the logical ID of this resource to the intrinsic `Ref` function, Ref returns the Id.

### Fn::GetAtt

The `Fn::GetAtt` intrinsic function returns a value for a specified attribute of this type. The following are the available attributes and sample return values.

For more information about using the `Fn::GetAtt` intrinsic function, see [Fn::GetAtt](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/intrinsic-function-reference-getatt.html).

#### Id

Id for Wireless Device Import Task, Returned upon successful start.

#### Arn

Arn for Wireless Device Import Task, Returned upon successful start.

#### CreationDate

CreationDate for import task

#### Status

Status for import task

#### StatusReason

StatusReason for import task

#### InitializedImportedDevicesCount

Initialized Imported Devices Count

#### PendingImportedDevicesCount

Pending Imported Devices Count

#### OnboardedImportedDevicesCount

Onboarded Imported Devices Count

#### FailedImportedDevicesCount

Failed Imported Devices Count

#### DeviceCreationFileList

Returns the <code>DeviceCreationFileList</code> value.
