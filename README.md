# git automatically merge develop branch into master on AWS Codecommit

## Codebuild  Role
   1) CloudWatchFullAccess
   2) AmazonEC2ContainerRegistryFullAccess
   3) AWSCodeCommitFullAccess 
   4) AmazonS3FullAccess
<table>   
        <td nowrap width="200" valign="top">
            <table>
                <tr>
                    <th align="left">Launch</th>
                </tr>
                <tr>
                    <td>
                        <a href="https://console.aws.amazon.com/cloudformation/home?#/stacks/new?&templateURL=https://electromech-cloudformation-templates.s3.ap-south-1.amazonaws.com/buildspec-repo-merge.yml" target="_blank"><img src="https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png"></a>
                    </td>
                </tr>
            </table>
        </td>
    </tr>
</table>
