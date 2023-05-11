# Using Git Actions To Deploy A Scene

This folder contains all the necessary files to launch a Decentraland scene.

You will find the github actions defined [here](https://github.com/decentraland-scenes/git-actions-auto-deploy/tree/develop/.github/workflows)

#### Using SDK7?
[Using SDK7? check here](https://github.com/decentraland-scenes/git-actions-auto-deploy-sdk7).  workflow actions for SDK7 do not change but package.json does a little

[https://github.com/decentraland-scenes/git-actions-auto-deploy-sdk7](https://github.com/decentraland-scenes/git-actions-auto-deploy-sdk7)

Steps

1. Decide which branch will be used to deploy a scene and update your git action file to target that branch
* Add the private key for the wallet that has operator rights (for a scene deployed in world) OR wallet that has the DCL name for which you will be deploying to worlds.
* Merge changes to the decided branch
* Check the action logs if deploy was successful

## Video Tutorial

[ https://youtu.be/desIuzZeBkc]( https://youtu.be/desIuzZeBkc)


## Try it out

**Install the CLI**

Download and install the Decentraland CLI by running the following command:

```bash
npm i -g decentraland
```

**Previewing the scene**

Open this folder on the command line, then run:

```
dcl start
```

Any dependencies are installed and then the CLI opens the scene in a new browser tab.

## Deploy to Decentraland

If you own any parcels of land in Decentraland, or have permissions to deploy to someone else's, you can publish this project.

1. Make sure the scene parcels in `scene.json` match those you own or have permissions on.
2. Run `dcl deploy` on the project folder
3. This will open a browser tab to confirm. Metamask will prompt you to sign.
   > Note: Make sure you are using the wallet that owns the parcels or has permissions.

### Deploy to a free server

If you don't own parcels in Decentraland or are not ready to publish your scene to the world, you can share your creations by uploading your scenes to a free hosting service.

See [Upload a preview](https://docs.decentraland.org/development-guide/deploy-to-now/) for instructions on how to do this.

## Resources

Learn more about how to build your own scenes in our [documentation](https://docs.decentraland.org/) site.

Find more example scenes, tutorials and helper libraries in the [Awesome Repository](https://github.com/decentraland-scenes/Awesome-Repository).

If you need any help, join [Decentraland's Discord](https://dcl.gg/discord), where you'll find a vibrant community of other creators who are eager to help. You're sure to find help in the #SDK support channel.

## Copyright info

This scene is protected with a standard Apache 2 licence. See the terms and conditions in the [LICENSE](/LICENSE) file.
