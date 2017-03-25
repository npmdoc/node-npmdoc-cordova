# api documentation for  cordova (v6.5.0)  [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-cordova.svg)](https://travis-ci.org/npmdoc/node-npmdoc-cordova)
#### Cordova command line interface tool

[![NPM](https://nodei.co/npm/cordova.png?downloads=true)](https://www.npmjs.com/package/cordova)

[![apidoc](https://npmdoc.github.io/node-npmdoc-cordova/build/screen-capture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-cordova_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-cordova/build..beta..travis-ci.org/apidoc.html)

![package-listing](https://npmdoc.github.io/node-npmdoc-cordova/build/screen-capture.npmPackageListing.svg)



# package.json

```json

{
    "author": {
        "name": "Anis Kadri"
    },
    "bin": {
        "cordova": "./bin/cordova"
    },
    "bugs": {
        "url": "https://issues.apache.org/jira/browse/CB",
        "email": "dev@cordova.apache.org"
    },
    "contributors": [
        {
            "name": "Brian LeRoux",
            "email": "b@brian.io"
        },
        {
            "name": "Fil Maj",
            "email": "maj.fil@gmail.com"
        },
        {
            "name": "Mike Reinstein",
            "email": "reinstein.mike@gmail.com"
        },
        {
            "name": "Darry Pogue",
            "email": "darryl@dpogue.ca"
        },
        {
            "name": "Michael Brooks",
            "email": "michael@michaelbrooks.ca"
        },
        {
            "name": "Braden Shepherdson",
            "email": "braden@chromium.org"
        },
        {
            "name": "Gord Tanner",
            "email": "gtanner@gmail.com"
        },
        {
            "name": "Tim Kim",
            "email": "timk@adobe.com"
        },
        {
            "name": "Benn Mapes",
            "email": "Benn.Mapes@gmail.com"
        },
        {
            "name": "Michael Wolf",
            "email": "Michael.Wolf@Cynergy.com"
        },
        {
            "name": "Andrew Grieve",
            "email": "agrieve@chromium.org"
        },
        {
            "name": "Bryan Higgins",
            "email": "bhiggins@blackberry.com"
        },
        {
            "name": "Don Coleman",
            "email": "dcoleman@chariotsolutions.com"
        },
        {
            "name": "Germano Gabbianelli",
            "email": "tyron.mx@gmail.com"
        },
        {
            "name": "Ian Clelland",
            "email": "iclelland@chromium.org"
        },
        {
            "name": "Lucas Holmqust",
            "email": "lholmqui@redhat.com"
        },
        {
            "name": "Matt LeGrand",
            "email": "mlegrand@gmail.com"
        },
        {
            "name": "Michal Mocny",
            "email": "mmocny@gmail.com"
        },
        {
            "name": "Sam Breed",
            "email": "sam@quickleft.com"
        },
        {
            "name": "Tommy-Carlos Williams",
            "email": "tommy@devgeeks.org"
        },
        {
            "name": "Rubén Norte",
            "email": "rubennorte@gmail.com"
        },
        {
            "name": "Germano Gabbianelli",
            "email": "tyrion.mx@gmail.com"
        },
        {
            "name": "Steven Gill",
            "email": "stevengill97@gmail.com"
        },
        {
            "name": "Jesse",
            "email": "purplecabbage@gmail.com"
        }
    ],
    "dependencies": {
        "cordova-common": "2.0.0",
        "cordova-lib": "6.5.0",
        "insight": "~0.8.2",
        "nopt": "3.0.1",
        "q": "1.0.1",
        "underscore": "1.7.0",
        "update-notifier": "^0.5.0"
    },
    "description": "Cordova command line interface tool",
    "devDependencies": {
        "istanbul": "^0.4.5",
        "jasmine": "^2.5.2",
        "jshint": "^2.9.4"
    },
    "directories": {},
    "dist": {
        "shasum": "e6ec81b17dd50c17c40b4b87330f7ced38fb0b47",
        "tarball": "https://registry.npmjs.org/cordova/-/cordova-6.5.0.tgz"
    },
    "engines": {
        "node": ">=4.0.0"
    },
    "keywords": [
        "cordova",
        "client",
        "cli"
    ],
    "license": "Apache-2.0",
    "main": "cordova",
    "maintainers": [
        {
            "name": "agrieve",
            "email": "agrieve@chromium.org"
        },
        {
            "name": "anis",
            "email": "anis.kadri@gmail.com"
        },
        {
            "name": "apachebuilds",
            "email": "root@apache.org"
        },
        {
            "name": "bennmapes",
            "email": "benn.mapes@gmail.com"
        },
        {
            "name": "bhiggins",
            "email": "bryan@bryanhiggins.net"
        },
        {
            "name": "bowserj",
            "email": "bowserj@apache.org"
        },
        {
            "name": "brianleroux",
            "email": "b@brian.io"
        },
        {
            "name": "cmarcelk",
            "email": "cmarcelk@gmail.com"
        },
        {
            "name": "filmaj",
            "email": "maj.fil@gmail.com"
        },
        {
            "name": "kamrik",
            "email": "kamrik@gmail.com"
        },
        {
            "name": "kotikov.vladimir",
            "email": "kotikov.vladimir@gmail.com"
        },
        {
            "name": "mmocny",
            "email": "mmocny@gmail.com"
        },
        {
            "name": "mwbrooks",
            "email": "michael@michaelbrooks.ca"
        },
        {
            "name": "purplecabbage",
            "email": "purplecabbage@gmail.com"
        },
        {
            "name": "sgrebnov",
            "email": "sergei.grebnov@gmail.com"
        },
        {
            "name": "shazron",
            "email": "shazron@gmail.com"
        },
        {
            "name": "shepheb",
            "email": "braden.shepherdson@gmail.com"
        },
        {
            "name": "stevegill",
            "email": "stevengill97@gmail.com"
        },
        {
            "name": "timbarham",
            "email": "npmjs@barhams.info"
        }
    ],
    "name": "cordova",
    "optionalDependencies": {},
    "preferGlobal": "true",
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "https://git-wip-us.apache.org/repos/asf/cordova-cli.git"
    },
    "scripts": {
        "cover": "istanbul cover --root src --print detail jasmine",
        "jasmine": "jasmine --captureExceptions --color",
        "jshint": "jshint spec && jshint src",
        "test": "npm run jshint && npm run jasmine"
    },
    "version": "6.5.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module cordova](#apidoc.module.cordova)
1.  [function <span class="apidocSignatureSpan">cordova.</span>build ()](#apidoc.element.cordova.build)
1.  [function <span class="apidocSignatureSpan">cordova.</span>clean ()](#apidoc.element.cordova.clean)
1.  [function <span class="apidocSignatureSpan">cordova.</span>cli (inputArgs, cb)](#apidoc.element.cordova.cli)
1.  [function <span class="apidocSignatureSpan">cordova.</span>compile ()](#apidoc.element.cordova.compile)
1.  [function <span class="apidocSignatureSpan">cordova.</span>cordova_lib.CordovaError (message, code, context)](#apidoc.element.cordova.cordova_lib.CordovaError)
1.  [function <span class="apidocSignatureSpan">cordova.</span>cordova_lib.PluginInfo (dirname)](#apidoc.element.cordova.cordova_lib.PluginInfo)
1.  [function <span class="apidocSignatureSpan">cordova.</span>cordova_lib.configparser (path)](#apidoc.element.cordova.cordova_lib.configparser)
1.  [function <span class="apidocSignatureSpan">cordova.</span>create ()](#apidoc.element.cordova.create)
1.  [function <span class="apidocSignatureSpan">cordova.</span>emit ()](#apidoc.element.cordova.emit)
1.  [function <span class="apidocSignatureSpan">cordova.</span>emulate ()](#apidoc.element.cordova.emulate)
1.  [function <span class="apidocSignatureSpan">cordova.</span>findProjectRoot (opt_startDir)](#apidoc.element.cordova.findProjectRoot)
1.  [function <span class="apidocSignatureSpan">cordova.</span>info ()](#apidoc.element.cordova.info)
1.  [function <span class="apidocSignatureSpan">cordova.</span>off ()](#apidoc.element.cordova.off)
1.  [function <span class="apidocSignatureSpan">cordova.</span>on ()](#apidoc.element.cordova.on)
1.  [function <span class="apidocSignatureSpan">cordova.</span>platform ()](#apidoc.element.cordova.platform)
1.  [function <span class="apidocSignatureSpan">cordova.</span>platforms ()](#apidoc.element.cordova.platforms)
1.  [function <span class="apidocSignatureSpan">cordova.</span>plugin ()](#apidoc.element.cordova.plugin)
1.  [function <span class="apidocSignatureSpan">cordova.</span>plugins ()](#apidoc.element.cordova.plugins)
1.  [function <span class="apidocSignatureSpan">cordova.</span>prepare ()](#apidoc.element.cordova.prepare)
1.  [function <span class="apidocSignatureSpan">cordova.</span>projectMetadata ()](#apidoc.element.cordova.projectMetadata)
1.  [function <span class="apidocSignatureSpan">cordova.</span>removeAllListeners ()](#apidoc.element.cordova.removeAllListeners)
1.  [function <span class="apidocSignatureSpan">cordova.</span>removeListener ()](#apidoc.element.cordova.removeListener)
1.  [function <span class="apidocSignatureSpan">cordova.</span>requirements ()](#apidoc.element.cordova.requirements)
1.  [function <span class="apidocSignatureSpan">cordova.</span>run ()](#apidoc.element.cordova.run)
1.  [function <span class="apidocSignatureSpan">cordova.</span>targets ()](#apidoc.element.cordova.targets)
1.  [function <span class="apidocSignatureSpan">cordova.</span>trigger ()](#apidoc.element.cordova.trigger)
1.  object <span class="apidocSignatureSpan">cordova.</span>cordova_lib
1.  object <span class="apidocSignatureSpan">cordova.</span>cordova_lib.CordovaError.prototype
1.  object <span class="apidocSignatureSpan">cordova.</span>cordova_lib.configparser.prototype
1.  object <span class="apidocSignatureSpan">cordova.</span>cordova_lib.events
1.  object <span class="apidocSignatureSpan">cordova.</span>raw
1.  string <span class="apidocSignatureSpan">cordova.</span>binname

#### [module cordova.cordova_lib](#apidoc.module.cordova.cordova_lib)
1.  [function <span class="apidocSignatureSpan">cordova.cordova_lib.</span>CordovaError (message, code, context)](#apidoc.element.cordova.cordova_lib.CordovaError)
1.  [function <span class="apidocSignatureSpan">cordova.cordova_lib.</span>PluginInfo (dirname)](#apidoc.element.cordova.cordova_lib.PluginInfo)
1.  [function <span class="apidocSignatureSpan">cordova.cordova_lib.</span>configparser (path)](#apidoc.element.cordova.cordova_lib.configparser)
1.  object <span class="apidocSignatureSpan">cordova.cordova_lib.</span>events
1.  string <span class="apidocSignatureSpan">cordova.cordova_lib.</span>binname

#### [module cordova.cordova_lib.CordovaError](#apidoc.module.cordova.cordova_lib.CordovaError)
1.  [function <span class="apidocSignatureSpan">cordova.cordova_lib.</span>CordovaError (message, code, context)](#apidoc.element.cordova.cordova_lib.CordovaError.CordovaError)
1.  number <span class="apidocSignatureSpan">cordova.cordova_lib.CordovaError.</span>EXTERNAL_TOOL_ERROR
1.  number <span class="apidocSignatureSpan">cordova.cordova_lib.CordovaError.</span>UNKNOWN_ERROR

#### [module cordova.cordova_lib.CordovaError.prototype](#apidoc.module.cordova.cordova_lib.CordovaError.prototype)
1.  [function <span class="apidocSignatureSpan">cordova.cordova_lib.CordovaError.prototype.</span>getErrorCodeName ()](#apidoc.element.cordova.cordova_lib.CordovaError.prototype.getErrorCodeName)
1.  [function <span class="apidocSignatureSpan">cordova.cordova_lib.CordovaError.prototype.</span>toString (isVerbose)](#apidoc.element.cordova.cordova_lib.CordovaError.prototype.toString)

#### [module cordova.cordova_lib.PluginInfo](#apidoc.module.cordova.cordova_lib.PluginInfo)
1.  [function <span class="apidocSignatureSpan">cordova.cordova_lib.</span>PluginInfo (dirname)](#apidoc.element.cordova.cordova_lib.PluginInfo.PluginInfo)
1.  [function <span class="apidocSignatureSpan">cordova.cordova_lib.PluginInfo.</span>loadPluginsDir (dir)](#apidoc.element.cordova.cordova_lib.PluginInfo.loadPluginsDir)

#### [module cordova.cordova_lib.configparser](#apidoc.module.cordova.cordova_lib.configparser)
1.  [function <span class="apidocSignatureSpan">cordova.cordova_lib.</span>configparser (path)](#apidoc.element.cordova.cordova_lib.configparser.configparser)

#### [module cordova.cordova_lib.configparser.prototype](#apidoc.module.cordova.cordova_lib.configparser.prototype)
1.  [function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>addElement (name, attributes)](#apidoc.element.cordova.cordova_lib.configparser.prototype.addElement)
1.  [function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>addEngine (name, spec)](#apidoc.element.cordova.cordova_lib.configparser.prototype.addEngine)
1.  [function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>addPlugin (attributes, variables)](#apidoc.element.cordova.cordova_lib.configparser.prototype.addPlugin)
1.  [function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>android_activityName ()](#apidoc.element.cordova.cordova_lib.configparser.prototype.android_activityName)
1.  [function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>android_packageName ()](#apidoc.element.cordova.cordova_lib.configparser.prototype.android_packageName)
1.  [function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>android_versionCode ()](#apidoc.element.cordova.cordova_lib.configparser.prototype.android_versionCode)
1.  [function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>author ()](#apidoc.element.cordova.cordova_lib.configparser.prototype.author)
1.  [function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>description ()](#apidoc.element.cordova.cordova_lib.configparser.prototype.description)
1.  [function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>getAccesses ()](#apidoc.element.cordova.cordova_lib.configparser.prototype.getAccesses)
1.  [function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>getAllowIntents ()](#apidoc.element.cordova.cordova_lib.configparser.prototype.getAllowIntents)
1.  [function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>getAllowNavigations ()](#apidoc.element.cordova.cordova_lib.configparser.prototype.getAllowNavigations)
1.  [function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>getAttribute (attr)](#apidoc.element.cordova.cordova_lib.configparser.prototype.getAttribute)
1.  [function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>getEditConfigs (platform)](#apidoc.element.cordova.cordova_lib.configparser.prototype.getEditConfigs)
1.  [function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>getEngines ()](#apidoc.element.cordova.cordova_lib.configparser.prototype.getEngines)
1.  [function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>getFileResources (platform)](#apidoc.element.cordova.cordova_lib.configparser.prototype.getFileResources)
1.  [function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>getGlobalPreference (name)](#apidoc.element.cordova.cordova_lib.configparser.prototype.getGlobalPreference)
1.  [function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>getHookScripts (hook, platforms)](#apidoc.element.cordova.cordova_lib.configparser.prototype.getHookScripts)
1.  [function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>getIcons (platform)](#apidoc.element.cordova.cordova_lib.configparser.prototype.getIcons)
1.  [function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>getPlatformPreference (name, platform)](#apidoc.element.cordova.cordova_lib.configparser.prototype.getPlatformPreference)
1.  [function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>getPlugin (id)](#apidoc.element.cordova.cordova_lib.configparser.prototype.getPlugin)
1.  [function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>getPluginIdList ()](#apidoc.element.cordova.cordova_lib.configparser.prototype.getPluginIdList)
1.  [function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>getPlugins ()](#apidoc.element.cordova.cordova_lib.configparser.prototype.getPlugins)
1.  [function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>getPreference (name, platform)](#apidoc.element.cordova.cordova_lib.configparser.prototype.getPreference)
1.  [function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>getSplashScreens (platform)](#apidoc.element.cordova.cordova_lib.configparser.prototype.getSplashScreens)
1.  [function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>getStaticResources (platform, resourceName)](#apidoc.element.cordova.cordova_lib.configparser.prototype.getStaticResources)
1.  [function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>ios_CFBundleIdentifier ()](#apidoc.element.cordova.cordova_lib.configparser.prototype.ios_CFBundleIdentifier)
1.  [function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>ios_CFBundleVersion ()](#apidoc.element.cordova.cordova_lib.configparser.prototype.ios_CFBundleVersion)
1.  [function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>name ()](#apidoc.element.cordova.cordova_lib.configparser.prototype.name)
1.  [function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>packageName (id)](#apidoc.element.cordova.cordova_lib.configparser.prototype.packageName)
1.  [function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>removeEngine (name)](#apidoc.element.cordova.cordova_lib.configparser.prototype.removeEngine)
1.  [function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>removePlugin (id)](#apidoc.element.cordova.cordova_lib.configparser.prototype.removePlugin)
1.  [function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>setDescription (text)](#apidoc.element.cordova.cordova_lib.configparser.prototype.setDescription)
1.  [function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>setGlobalPreference (name, value)](#apidoc.element.cordova.cordova_lib.configparser.prototype.setGlobalPreference)
1.  [function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>setName (name)](#apidoc.element.cordova.cordova_lib.configparser.prototype.setName)
1.  [function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>setPackageName (id)](#apidoc.element.cordova.cordova_lib.configparser.prototype.setPackageName)
1.  [function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>setVersion (value)](#apidoc.element.cordova.cordova_lib.configparser.prototype.setVersion)
1.  [function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>version ()](#apidoc.element.cordova.cordova_lib.configparser.prototype.version)
1.  [function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>windows_packageVersion ()](#apidoc.element.cordova.cordova_lib.configparser.prototype.windows_packageVersion)
1.  [function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>write ()](#apidoc.element.cordova.cordova_lib.configparser.prototype.write)

#### [module cordova.cordova_lib.events](#apidoc.module.cordova.cordova_lib.events)
1.  [function <span class="apidocSignatureSpan">cordova.cordova_lib.events.</span>emit ()](#apidoc.element.cordova.cordova_lib.events.emit)
1.  [function <span class="apidocSignatureSpan">cordova.cordova_lib.events.</span>forwardEventsTo (eventEmitter)](#apidoc.element.cordova.cordova_lib.events.forwardEventsTo)
1.  number <span class="apidocSignatureSpan">cordova.cordova_lib.events.</span>_eventsCount
1.  object <span class="apidocSignatureSpan">cordova.cordova_lib.events.</span>_events
1.  object <span class="apidocSignatureSpan">cordova.cordova_lib.events.</span>domain



# <a name="apidoc.module.cordova"></a>[module cordova](#apidoc.module.cordova)

#### <a name="apidoc.element.cordova.build"></a>[function <span class="apidocSignatureSpan">cordova.</span>build ()](#apidoc.element.cordova.build)
- description and source-code
```javascript
build = function () {
    val = val || module.require(modulePath);
    if (arguments.length && typeof arguments[arguments.length - 1] === 'function') {
        // If args exist and the last one is a function, it's the callback.
        var args = Array.prototype.slice.call(arguments);
        var cb = args.pop();
        val.apply(module.exports, args).done(function(result) { cb(undefined, result); }, cb);
    } else {
        val.apply(module.exports, arguments).done(null, function(err) { throw err; });
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cordova.clean"></a>[function <span class="apidocSignatureSpan">cordova.</span>clean ()](#apidoc.element.cordova.clean)
- description and source-code
```javascript
clean = function () {
    val = val || module.require(modulePath);
    if (arguments.length && typeof arguments[arguments.length - 1] === 'function') {
        // If args exist and the last one is a function, it's the callback.
        var args = Array.prototype.slice.call(arguments);
        var cb = args.pop();
        val.apply(module.exports, args).done(function(result) { cb(undefined, result); }, cb);
    } else {
        val.apply(module.exports, arguments).done(null, function(err) { throw err; });
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cordova.cli"></a>[function <span class="apidocSignatureSpan">cordova.</span>cli (inputArgs, cb)](#apidoc.element.cordova.cli)
- description and source-code
```javascript
cli = function (inputArgs, cb) {

<span class="apidocCodeCommentSpan">    /**
     * mainly used for testing.
     */
</span>    cb = cb || function(){};

    init();

    // If no inputArgs given, use process.argv.
    inputArgs = inputArgs || process.argv;
    var cmd = inputArgs[2]; // e.g: inputArgs= 'node cordova run ios'
    var subcommand = getSubCommand(inputArgs, cmd);
    var isTelemetryCmd = (cmd === 'telemetry');

    // ToDO: Move nopt-based parsing of args up here
    if(cmd === '--version' || cmd === '-v') {
        cmd = 'version';
    } else if(!cmd || cmd === '--help' || cmd === 'h') {
        cmd = 'help';
    }

    Q().then(function() {

        /**
         * Skip telemetry prompt if:
         * - CI environment variable is present
         * - Command is run with '--no-telemetry' flag
         * - Command ran is: 'cordova telemetry on | off | ...'
         */

        if(telemetry.isCI(process.env) || telemetry.isNoTelemetryFlag(inputArgs)) {
            return Q(false);
        }

        /**
         * We shouldn't prompt for telemetry if user issues a command of the form: 'cordova telemetry on | off | ...x'
         * Also, if the user has already been prompted and made a decision, use his saved answer
         */
        if(isTelemetryCmd) {
            var isOptedIn = telemetry.isOptedIn();
            return handleTelemetryCmd(subcommand, isOptedIn);
        }

        if(telemetry.hasUserOptedInOrOut()) {
            return Q(telemetry.isOptedIn());
        }

        /**
         * Otherwise, prompt user to opt-in or out
         * Note: the prompt is shown for 30 seconds. If no choice is made by that time, User is considered to have opted out.
         */
        return telemetry.showPrompt();
    }).then(function (collectTelemetry) {
        shouldCollectTelemetry = collectTelemetry;
        if(isTelemetryCmd) {
            return Q();
        }
        return cli(inputArgs);
    }).then(function () {
        if (shouldCollectTelemetry && !isTelemetryCmd) {
            telemetry.track(cmd, subcommand, 'successful');
        }
        // call cb with error as arg if something failed
        cb(null);
    }).fail(function (err) {
        if (shouldCollectTelemetry && !isTelemetryCmd) {
            telemetry.track(cmd, subcommand, 'unsuccessful');
        }
        // call cb with error as arg if something failed
        cb(err);
        throw err;
    }).done();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cordova.compile"></a>[function <span class="apidocSignatureSpan">cordova.</span>compile ()](#apidoc.element.cordova.compile)
- description and source-code
```javascript
compile = function () {
    val = val || module.require(modulePath);
    if (arguments.length && typeof arguments[arguments.length - 1] === 'function') {
        // If args exist and the last one is a function, it's the callback.
        var args = Array.prototype.slice.call(arguments);
        var cb = args.pop();
        val.apply(module.exports, args).done(function(result) { cb(undefined, result); }, cb);
    } else {
        val.apply(module.exports, arguments).done(null, function(err) { throw err; });
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cordova.cordova_lib.CordovaError"></a>[function <span class="apidocSignatureSpan">cordova.</span>cordova_lib.CordovaError (message, code, context)](#apidoc.element.cordova.cordova_lib.CordovaError)
- description and source-code
```javascript
function CordovaError(message, code, context) {
    Error.captureStackTrace(this, this.constructor);
    this.name = this.constructor.name;
    this.message = message;
    this.code = code || CordovaError.UNKNOWN_ERROR;
    this.context = context;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cordova.cordova_lib.PluginInfo"></a>[function <span class="apidocSignatureSpan">cordova.</span>cordova_lib.PluginInfo (dirname)](#apidoc.element.cordova.cordova_lib.PluginInfo)
- description and source-code
```javascript
function PluginInfo(dirname) {
    var self = this;

    // METHODS
    // Defined inside the constructor to avoid the "this" binding problems.

    // <preference> tag
    // Example: <preference name="API_KEY" />
    // Used to require a variable to be specified via --variable when installing the plugin.
    // returns { key : default | null}
    self.getPreferences = getPreferences;
    function getPreferences(platform) {
        return _getTags(self._et, 'preference', platform, _parsePreference)
        .reduce(function (preferences, pref) {
            preferences[pref.preference] = pref.default;
            return preferences;
        }, {});
    }

    function _parsePreference(prefTag) {
        var name = prefTag.attrib.name.toUpperCase();
        var def = prefTag.attrib.default || null;
        return {preference: name, default: def};
    }

    // <asset>
    self.getAssets = getAssets;
    function getAssets(platform) {
        var assets = _getTags(self._et, 'asset', platform, _parseAsset);
        return assets;
    }

    function _parseAsset(tag) {
        var src = tag.attrib.src;
        var target = tag.attrib.target;

        if ( !src || !target) {
            var msg =
                'Malformed <asset> tag. Both "src" and "target" attributes'
                + 'must be specified in\n'
                + self.filepath
                ;
            throw new Error(msg);
        }

        var asset = {
            itemType: 'asset',
            src: src,
            target: target
        };
        return asset;
    }


    // <dependency>
    // Example:
    // <dependency id="com.plugin.id"
    //     url="https://github.com/myuser/someplugin"
    //     commit="428931ada3891801"
    //     subdir="some/path/here" />
    self.getDependencies = getDependencies;
    function getDependencies(platform) {
        var deps = _getTags(
                self._et,
                'dependency',
                platform,
                _parseDependency
        );
        return deps;
    }

    function _parseDependency(tag) {
        var dep =
            { id : tag.attrib.id
            , url : tag.attrib.url || ''
            , subdir : tag.attrib.subdir || ''
            , commit : tag.attrib.commit
            };

        dep.git_ref = dep.commit;

        if ( !dep.id ) {
            var msg =
                '<dependency> tag is missing id attribute in '
                + self.filepath
                ;
            throw new CordovaError(msg);
        }
        return dep;
    }


    // <config-file> tag
    self.getConfigFiles = getConfigFiles;
    function getConfigFiles(platform) {
        var configFiles = _getTags(self._et, 'config-file', platform, _parseConfigFile);
        return configFiles;
    }

    function _parseConfigFile(tag) {
        var configFile =
            { target : tag.attrib['target']
            , parent : tag.attrib['parent']
            , after : tag.attrib['after']
            , xmls : tag.getchildren()
            // To support demuxing via versions
            , versions : tag.attrib['versions']
            , deviceTarget: tag.attrib['device-target']
            };
        return configFile;
    }

    self.getEditConfigs = getEditConfigs;
    function getEditConfigs(platform) {
        var editConfigs = _getTags(self._et, 'edit-config', platform, _parseEditConfigs);
        return editConfigs;
    }

    function _parseEditConfigs(tag) {
        var editConfig =
        { file : tag.attrib['file']
        , target : tag.attrib['target']
        , mode : tag.attrib['mode']
        , xmls : tag.getchildren()
        };
        return editConfig;
    }

    // <info> tags, both global and within a <platform>
    // TODO (kamrik): Do we ever use <info> under <platform>? Example wanted.
    self.getInfo = getInfo;
    function getInfo(platform) {
        var infos = _getTags(
                self._et,
                'info',
                platform,
                function(elem) { return elem.text; }
        );
        // Filter out any undefined or empty strings. ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cordova.cordova_lib.configparser"></a>[function <span class="apidocSignatureSpan">cordova.</span>cordova_lib.configparser (path)](#apidoc.element.cordova.cordova_lib.configparser)
- description and source-code
```javascript
function ConfigParser(path) {
    this.path = path;
    try {
        this.doc = xml.parseElementtreeSync(path);
        this.cdvNamespacePrefix = getCordovaNamespacePrefix(this.doc);
        et.register_namespace(this.cdvNamespacePrefix, 'http://cordova.apache.org/ns/1.0');
    } catch (e) {
        console.error('Parsing '+path+' failed');
        throw e;
    }
    var r = this.doc.getroot();
    if (r.tag !== 'widget') {
        throw new CordovaError(path + ' has incorrect root node name (expected "widget", was "' + r.tag + '")');
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cordova.create"></a>[function <span class="apidocSignatureSpan">cordova.</span>create ()](#apidoc.element.cordova.create)
- description and source-code
```javascript
create = function () {
    val = val || module.require(modulePath);
    if (arguments.length && typeof arguments[arguments.length - 1] === 'function') {
        // If args exist and the last one is a function, it's the callback.
        var args = Array.prototype.slice.call(arguments);
        var cb = args.pop();
        val.apply(module.exports, args).done(function(result) { cb(undefined, result); }, cb);
    } else {
        val.apply(module.exports, arguments).done(null, function(err) { throw err; });
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cordova.emit"></a>[function <span class="apidocSignatureSpan">cordova.</span>emit ()](#apidoc.element.cordova.emit)
- description and source-code
```javascript
emit = function () {
    cordova_events.emit.apply(cordova_events, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cordova.emulate"></a>[function <span class="apidocSignatureSpan">cordova.</span>emulate ()](#apidoc.element.cordova.emulate)
- description and source-code
```javascript
emulate = function () {
    val = val || module.require(modulePath);
    if (arguments.length && typeof arguments[arguments.length - 1] === 'function') {
        // If args exist and the last one is a function, it's the callback.
        var args = Array.prototype.slice.call(arguments);
        var cb = args.pop();
        val.apply(module.exports, args).done(function(result) { cb(undefined, result); }, cb);
    } else {
        val.apply(module.exports, arguments).done(null, function(err) { throw err; });
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cordova.findProjectRoot"></a>[function <span class="apidocSignatureSpan">cordova.</span>findProjectRoot (opt_startDir)](#apidoc.element.cordova.findProjectRoot)
- description and source-code
```javascript
findProjectRoot = function (opt_startDir) {
    return cordova_util.isCordova(opt_startDir);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cordova.info"></a>[function <span class="apidocSignatureSpan">cordova.</span>info ()](#apidoc.element.cordova.info)
- description and source-code
```javascript
info = function () {
    val = val || module.require(modulePath);
    if (arguments.length && typeof arguments[arguments.length - 1] === 'function') {
        // If args exist and the last one is a function, it's the callback.
        var args = Array.prototype.slice.call(arguments);
        var cb = args.pop();
        val.apply(module.exports, args).done(function(result) { cb(undefined, result); }, cb);
    } else {
        val.apply(module.exports, arguments).done(null, function(err) { throw err; });
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cordova.off"></a>[function <span class="apidocSignatureSpan">cordova.</span>off ()](#apidoc.element.cordova.off)
- description and source-code
```javascript
off = function () {
    cordova_events.removeListener.apply(cordova_events, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cordova.on"></a>[function <span class="apidocSignatureSpan">cordova.</span>on ()](#apidoc.element.cordova.on)
- description and source-code
```javascript
on = function () {
    cordova_events.on.apply(cordova_events, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cordova.platform"></a>[function <span class="apidocSignatureSpan">cordova.</span>platform ()](#apidoc.element.cordova.platform)
- description and source-code
```javascript
platform = function () {
    val = val || module.require(modulePath);
    if (arguments.length && typeof arguments[arguments.length - 1] === 'function') {
        // If args exist and the last one is a function, it's the callback.
        var args = Array.prototype.slice.call(arguments);
        var cb = args.pop();
        val.apply(module.exports, args).done(function(result) { cb(undefined, result); }, cb);
    } else {
        val.apply(module.exports, arguments).done(null, function(err) { throw err; });
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cordova.platforms"></a>[function <span class="apidocSignatureSpan">cordova.</span>platforms ()](#apidoc.element.cordova.platforms)
- description and source-code
```javascript
platforms = function () {
    val = val || module.require(modulePath);
    if (arguments.length && typeof arguments[arguments.length - 1] === 'function') {
        // If args exist and the last one is a function, it's the callback.
        var args = Array.prototype.slice.call(arguments);
        var cb = args.pop();
        val.apply(module.exports, args).done(function(result) { cb(undefined, result); }, cb);
    } else {
        val.apply(module.exports, arguments).done(null, function(err) { throw err; });
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cordova.plugin"></a>[function <span class="apidocSignatureSpan">cordova.</span>plugin ()](#apidoc.element.cordova.plugin)
- description and source-code
```javascript
plugin = function () {
    val = val || module.require(modulePath);
    if (arguments.length && typeof arguments[arguments.length - 1] === 'function') {
        // If args exist and the last one is a function, it's the callback.
        var args = Array.prototype.slice.call(arguments);
        var cb = args.pop();
        val.apply(module.exports, args).done(function(result) { cb(undefined, result); }, cb);
    } else {
        val.apply(module.exports, arguments).done(null, function(err) { throw err; });
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cordova.plugins"></a>[function <span class="apidocSignatureSpan">cordova.</span>plugins ()](#apidoc.element.cordova.plugins)
- description and source-code
```javascript
plugins = function () {
    val = val || module.require(modulePath);
    if (arguments.length && typeof arguments[arguments.length - 1] === 'function') {
        // If args exist and the last one is a function, it's the callback.
        var args = Array.prototype.slice.call(arguments);
        var cb = args.pop();
        val.apply(module.exports, args).done(function(result) { cb(undefined, result); }, cb);
    } else {
        val.apply(module.exports, arguments).done(null, function(err) { throw err; });
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cordova.prepare"></a>[function <span class="apidocSignatureSpan">cordova.</span>prepare ()](#apidoc.element.cordova.prepare)
- description and source-code
```javascript
prepare = function () {
    val = val || module.require(modulePath);
    if (arguments.length && typeof arguments[arguments.length - 1] === 'function') {
        // If args exist and the last one is a function, it's the callback.
        var args = Array.prototype.slice.call(arguments);
        var cb = args.pop();
        val.apply(module.exports, args).done(function(result) { cb(undefined, result); }, cb);
    } else {
        val.apply(module.exports, arguments).done(null, function(err) { throw err; });
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cordova.projectMetadata"></a>[function <span class="apidocSignatureSpan">cordova.</span>projectMetadata ()](#apidoc.element.cordova.projectMetadata)
- description and source-code
```javascript
projectMetadata = function () {
    val = val || module.require(modulePath);
    if (arguments.length && typeof arguments[arguments.length - 1] === 'function') {
        // If args exist and the last one is a function, it's the callback.
        var args = Array.prototype.slice.call(arguments);
        var cb = args.pop();
        val.apply(module.exports, args).done(function(result) { cb(undefined, result); }, cb);
    } else {
        val.apply(module.exports, arguments).done(null, function(err) { throw err; });
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cordova.removeAllListeners"></a>[function <span class="apidocSignatureSpan">cordova.</span>removeAllListeners ()](#apidoc.element.cordova.removeAllListeners)
- description and source-code
```javascript
removeAllListeners = function () {
    cordova_events.removeAllListeners.apply(cordova_events, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cordova.removeListener"></a>[function <span class="apidocSignatureSpan">cordova.</span>removeListener ()](#apidoc.element.cordova.removeListener)
- description and source-code
```javascript
removeListener = function () {
    cordova_events.removeListener.apply(cordova_events, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cordova.requirements"></a>[function <span class="apidocSignatureSpan">cordova.</span>requirements ()](#apidoc.element.cordova.requirements)
- description and source-code
```javascript
requirements = function () {
    val = val || module.require(modulePath);
    if (arguments.length && typeof arguments[arguments.length - 1] === 'function') {
        // If args exist and the last one is a function, it's the callback.
        var args = Array.prototype.slice.call(arguments);
        var cb = args.pop();
        val.apply(module.exports, args).done(function(result) { cb(undefined, result); }, cb);
    } else {
        val.apply(module.exports, arguments).done(null, function(err) { throw err; });
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cordova.run"></a>[function <span class="apidocSignatureSpan">cordova.</span>run ()](#apidoc.element.cordova.run)
- description and source-code
```javascript
run = function () {
    val = val || module.require(modulePath);
    if (arguments.length && typeof arguments[arguments.length - 1] === 'function') {
        // If args exist and the last one is a function, it's the callback.
        var args = Array.prototype.slice.call(arguments);
        var cb = args.pop();
        val.apply(module.exports, args).done(function(result) { cb(undefined, result); }, cb);
    } else {
        val.apply(module.exports, arguments).done(null, function(err) { throw err; });
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cordova.targets"></a>[function <span class="apidocSignatureSpan">cordova.</span>targets ()](#apidoc.element.cordova.targets)
- description and source-code
```javascript
targets = function () {
    val = val || module.require(modulePath);
    if (arguments.length && typeof arguments[arguments.length - 1] === 'function') {
        // If args exist and the last one is a function, it's the callback.
        var args = Array.prototype.slice.call(arguments);
        var cb = args.pop();
        val.apply(module.exports, args).done(function(result) { cb(undefined, result); }, cb);
    } else {
        val.apply(module.exports, arguments).done(null, function(err) { throw err; });
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cordova.trigger"></a>[function <span class="apidocSignatureSpan">cordova.</span>trigger ()](#apidoc.element.cordova.trigger)
- description and source-code
```javascript
trigger = function () {
    cordova_events.emit.apply(cordova_events, arguments);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.cordova.cordova_lib"></a>[module cordova.cordova_lib](#apidoc.module.cordova.cordova_lib)

#### <a name="apidoc.element.cordova.cordova_lib.CordovaError"></a>[function <span class="apidocSignatureSpan">cordova.cordova_lib.</span>CordovaError (message, code, context)](#apidoc.element.cordova.cordova_lib.CordovaError)
- description and source-code
```javascript
function CordovaError(message, code, context) {
    Error.captureStackTrace(this, this.constructor);
    this.name = this.constructor.name;
    this.message = message;
    this.code = code || CordovaError.UNKNOWN_ERROR;
    this.context = context;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cordova.cordova_lib.PluginInfo"></a>[function <span class="apidocSignatureSpan">cordova.cordova_lib.</span>PluginInfo (dirname)](#apidoc.element.cordova.cordova_lib.PluginInfo)
- description and source-code
```javascript
function PluginInfo(dirname) {
    var self = this;

    // METHODS
    // Defined inside the constructor to avoid the "this" binding problems.

    // <preference> tag
    // Example: <preference name="API_KEY" />
    // Used to require a variable to be specified via --variable when installing the plugin.
    // returns { key : default | null}
    self.getPreferences = getPreferences;
    function getPreferences(platform) {
        return _getTags(self._et, 'preference', platform, _parsePreference)
        .reduce(function (preferences, pref) {
            preferences[pref.preference] = pref.default;
            return preferences;
        }, {});
    }

    function _parsePreference(prefTag) {
        var name = prefTag.attrib.name.toUpperCase();
        var def = prefTag.attrib.default || null;
        return {preference: name, default: def};
    }

    // <asset>
    self.getAssets = getAssets;
    function getAssets(platform) {
        var assets = _getTags(self._et, 'asset', platform, _parseAsset);
        return assets;
    }

    function _parseAsset(tag) {
        var src = tag.attrib.src;
        var target = tag.attrib.target;

        if ( !src || !target) {
            var msg =
                'Malformed <asset> tag. Both "src" and "target" attributes'
                + 'must be specified in\n'
                + self.filepath
                ;
            throw new Error(msg);
        }

        var asset = {
            itemType: 'asset',
            src: src,
            target: target
        };
        return asset;
    }


    // <dependency>
    // Example:
    // <dependency id="com.plugin.id"
    //     url="https://github.com/myuser/someplugin"
    //     commit="428931ada3891801"
    //     subdir="some/path/here" />
    self.getDependencies = getDependencies;
    function getDependencies(platform) {
        var deps = _getTags(
                self._et,
                'dependency',
                platform,
                _parseDependency
        );
        return deps;
    }

    function _parseDependency(tag) {
        var dep =
            { id : tag.attrib.id
            , url : tag.attrib.url || ''
            , subdir : tag.attrib.subdir || ''
            , commit : tag.attrib.commit
            };

        dep.git_ref = dep.commit;

        if ( !dep.id ) {
            var msg =
                '<dependency> tag is missing id attribute in '
                + self.filepath
                ;
            throw new CordovaError(msg);
        }
        return dep;
    }


    // <config-file> tag
    self.getConfigFiles = getConfigFiles;
    function getConfigFiles(platform) {
        var configFiles = _getTags(self._et, 'config-file', platform, _parseConfigFile);
        return configFiles;
    }

    function _parseConfigFile(tag) {
        var configFile =
            { target : tag.attrib['target']
            , parent : tag.attrib['parent']
            , after : tag.attrib['after']
            , xmls : tag.getchildren()
            // To support demuxing via versions
            , versions : tag.attrib['versions']
            , deviceTarget: tag.attrib['device-target']
            };
        return configFile;
    }

    self.getEditConfigs = getEditConfigs;
    function getEditConfigs(platform) {
        var editConfigs = _getTags(self._et, 'edit-config', platform, _parseEditConfigs);
        return editConfigs;
    }

    function _parseEditConfigs(tag) {
        var editConfig =
        { file : tag.attrib['file']
        , target : tag.attrib['target']
        , mode : tag.attrib['mode']
        , xmls : tag.getchildren()
        };
        return editConfig;
    }

    // <info> tags, both global and within a <platform>
    // TODO (kamrik): Do we ever use <info> under <platform>? Example wanted.
    self.getInfo = getInfo;
    function getInfo(platform) {
        var infos = _getTags(
                self._et,
                'info',
                platform,
                function(elem) { return elem.text; }
        );
        // Filter out any undefined or empty strings. ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cordova.cordova_lib.configparser"></a>[function <span class="apidocSignatureSpan">cordova.cordova_lib.</span>configparser (path)](#apidoc.element.cordova.cordova_lib.configparser)
- description and source-code
```javascript
function ConfigParser(path) {
    this.path = path;
    try {
        this.doc = xml.parseElementtreeSync(path);
        this.cdvNamespacePrefix = getCordovaNamespacePrefix(this.doc);
        et.register_namespace(this.cdvNamespacePrefix, 'http://cordova.apache.org/ns/1.0');
    } catch (e) {
        console.error('Parsing '+path+' failed');
        throw e;
    }
    var r = this.doc.getroot();
    if (r.tag !== 'widget') {
        throw new CordovaError(path + ' has incorrect root node name (expected "widget", was "' + r.tag + '")');
    }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.cordova.cordova_lib.CordovaError"></a>[module cordova.cordova_lib.CordovaError](#apidoc.module.cordova.cordova_lib.CordovaError)

#### <a name="apidoc.element.cordova.cordova_lib.CordovaError.CordovaError"></a>[function <span class="apidocSignatureSpan">cordova.cordova_lib.</span>CordovaError (message, code, context)](#apidoc.element.cordova.cordova_lib.CordovaError.CordovaError)
- description and source-code
```javascript
function CordovaError(message, code, context) {
    Error.captureStackTrace(this, this.constructor);
    this.name = this.constructor.name;
    this.message = message;
    this.code = code || CordovaError.UNKNOWN_ERROR;
    this.context = context;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.cordova.cordova_lib.CordovaError.prototype"></a>[module cordova.cordova_lib.CordovaError.prototype](#apidoc.module.cordova.cordova_lib.CordovaError.prototype)

#### <a name="apidoc.element.cordova.cordova_lib.CordovaError.prototype.getErrorCodeName"></a>[function <span class="apidocSignatureSpan">cordova.cordova_lib.CordovaError.prototype.</span>getErrorCodeName ()](#apidoc.element.cordova.cordova_lib.CordovaError.prototype.getErrorCodeName)
- description and source-code
```javascript
getErrorCodeName = function () {
    for(var key in CordovaError) {
        if(CordovaError.hasOwnProperty(key)) {
            if(CordovaError[key] === this.code) {
                return key;
            }
        }
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cordova.cordova_lib.CordovaError.prototype.toString"></a>[function <span class="apidocSignatureSpan">cordova.cordova_lib.CordovaError.prototype.</span>toString (isVerbose)](#apidoc.element.cordova.cordova_lib.CordovaError.prototype.toString)
- description and source-code
```javascript
toString = function (isVerbose) {
    var message = '', codePrefix = '';

    if(this.code !== CordovaError.UNKNOWN_ERROR) {
        codePrefix = 'code: ' + this.code + (isVerbose ? (' (' + this.getErrorCodeName() + ')') : '') + ' ';
    }

    if(this.code === CordovaError.EXTERNAL_TOOL_ERROR) {
        if(typeof this.context !== 'undefined') {
            if(isVerbose) {
                message = codePrefix + EOL + this.context.toString(isVerbose) + '\n failed with an error: ' +
                    this.message + EOL + 'Stack trace: ' + this.stack;
            } else {
                message = codePrefix + '\'' + this.context.toString(isVerbose) + '\' ' + this.message;
            }
        } else {
            message = 'External tool failed with an error: ' + this.message;
        }
    } else {
        message = isVerbose ? codePrefix + this.stack : codePrefix + this.message;
    }

    return message;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.cordova.cordova_lib.PluginInfo"></a>[module cordova.cordova_lib.PluginInfo](#apidoc.module.cordova.cordova_lib.PluginInfo)

#### <a name="apidoc.element.cordova.cordova_lib.PluginInfo.PluginInfo"></a>[function <span class="apidocSignatureSpan">cordova.cordova_lib.</span>PluginInfo (dirname)](#apidoc.element.cordova.cordova_lib.PluginInfo.PluginInfo)
- description and source-code
```javascript
function PluginInfo(dirname) {
    var self = this;

    // METHODS
    // Defined inside the constructor to avoid the "this" binding problems.

    // <preference> tag
    // Example: <preference name="API_KEY" />
    // Used to require a variable to be specified via --variable when installing the plugin.
    // returns { key : default | null}
    self.getPreferences = getPreferences;
    function getPreferences(platform) {
        return _getTags(self._et, 'preference', platform, _parsePreference)
        .reduce(function (preferences, pref) {
            preferences[pref.preference] = pref.default;
            return preferences;
        }, {});
    }

    function _parsePreference(prefTag) {
        var name = prefTag.attrib.name.toUpperCase();
        var def = prefTag.attrib.default || null;
        return {preference: name, default: def};
    }

    // <asset>
    self.getAssets = getAssets;
    function getAssets(platform) {
        var assets = _getTags(self._et, 'asset', platform, _parseAsset);
        return assets;
    }

    function _parseAsset(tag) {
        var src = tag.attrib.src;
        var target = tag.attrib.target;

        if ( !src || !target) {
            var msg =
                'Malformed <asset> tag. Both "src" and "target" attributes'
                + 'must be specified in\n'
                + self.filepath
                ;
            throw new Error(msg);
        }

        var asset = {
            itemType: 'asset',
            src: src,
            target: target
        };
        return asset;
    }


    // <dependency>
    // Example:
    // <dependency id="com.plugin.id"
    //     url="https://github.com/myuser/someplugin"
    //     commit="428931ada3891801"
    //     subdir="some/path/here" />
    self.getDependencies = getDependencies;
    function getDependencies(platform) {
        var deps = _getTags(
                self._et,
                'dependency',
                platform,
                _parseDependency
        );
        return deps;
    }

    function _parseDependency(tag) {
        var dep =
            { id : tag.attrib.id
            , url : tag.attrib.url || ''
            , subdir : tag.attrib.subdir || ''
            , commit : tag.attrib.commit
            };

        dep.git_ref = dep.commit;

        if ( !dep.id ) {
            var msg =
                '<dependency> tag is missing id attribute in '
                + self.filepath
                ;
            throw new CordovaError(msg);
        }
        return dep;
    }


    // <config-file> tag
    self.getConfigFiles = getConfigFiles;
    function getConfigFiles(platform) {
        var configFiles = _getTags(self._et, 'config-file', platform, _parseConfigFile);
        return configFiles;
    }

    function _parseConfigFile(tag) {
        var configFile =
            { target : tag.attrib['target']
            , parent : tag.attrib['parent']
            , after : tag.attrib['after']
            , xmls : tag.getchildren()
            // To support demuxing via versions
            , versions : tag.attrib['versions']
            , deviceTarget: tag.attrib['device-target']
            };
        return configFile;
    }

    self.getEditConfigs = getEditConfigs;
    function getEditConfigs(platform) {
        var editConfigs = _getTags(self._et, 'edit-config', platform, _parseEditConfigs);
        return editConfigs;
    }

    function _parseEditConfigs(tag) {
        var editConfig =
        { file : tag.attrib['file']
        , target : tag.attrib['target']
        , mode : tag.attrib['mode']
        , xmls : tag.getchildren()
        };
        return editConfig;
    }

    // <info> tags, both global and within a <platform>
    // TODO (kamrik): Do we ever use <info> under <platform>? Example wanted.
    self.getInfo = getInfo;
    function getInfo(platform) {
        var infos = _getTags(
                self._et,
                'info',
                platform,
                function(elem) { return elem.text; }
        );
        // Filter out any undefined or empty strings. ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cordova.cordova_lib.PluginInfo.loadPluginsDir"></a>[function <span class="apidocSignatureSpan">cordova.cordova_lib.PluginInfo.</span>loadPluginsDir (dir)](#apidoc.element.cordova.cordova_lib.PluginInfo.loadPluginsDir)
- description and source-code
```javascript
loadPluginsDir = function (dir) {
    var PluginInfoProvider = require('./PluginInfoProvider');
    return new PluginInfoProvider().getAllWithinSearchPath(dir);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.cordova.cordova_lib.configparser"></a>[module cordova.cordova_lib.configparser](#apidoc.module.cordova.cordova_lib.configparser)

#### <a name="apidoc.element.cordova.cordova_lib.configparser.configparser"></a>[function <span class="apidocSignatureSpan">cordova.cordova_lib.</span>configparser (path)](#apidoc.element.cordova.cordova_lib.configparser.configparser)
- description and source-code
```javascript
function ConfigParser(path) {
    this.path = path;
    try {
        this.doc = xml.parseElementtreeSync(path);
        this.cdvNamespacePrefix = getCordovaNamespacePrefix(this.doc);
        et.register_namespace(this.cdvNamespacePrefix, 'http://cordova.apache.org/ns/1.0');
    } catch (e) {
        console.error('Parsing '+path+' failed');
        throw e;
    }
    var r = this.doc.getroot();
    if (r.tag !== 'widget') {
        throw new CordovaError(path + ' has incorrect root node name (expected "widget", was "' + r.tag + '")');
    }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.cordova.cordova_lib.configparser.prototype"></a>[module cordova.cordova_lib.configparser.prototype](#apidoc.module.cordova.cordova_lib.configparser.prototype)

#### <a name="apidoc.element.cordova.cordova_lib.configparser.prototype.addElement"></a>[function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>addElement (name, attributes)](#apidoc.element.cordova.cordova_lib.configparser.prototype.addElement)
- description and source-code
```javascript
addElement = function (name, attributes) {
    var el = et.Element(name);
    for (var a in attributes) {
        el.attrib[a] = attributes[a];
    }
    this.doc.getroot().append(el);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cordova.cordova_lib.configparser.prototype.addEngine"></a>[function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>addEngine (name, spec)](#apidoc.element.cordova.cordova_lib.configparser.prototype.addEngine)
- description and source-code
```javascript
addEngine = function (name, spec){
    if(!name) return;
    var el = et.Element('engine');
    el.attrib.name = name;
    if(spec){
        el.attrib.spec = spec;
    }
    this.doc.getroot().append(el);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cordova.cordova_lib.configparser.prototype.addPlugin"></a>[function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>addPlugin (attributes, variables)](#apidoc.element.cordova.cordova_lib.configparser.prototype.addPlugin)
- description and source-code
```javascript
addPlugin = function (attributes, variables) {
    if (!attributes && !attributes.name) return;
    var el = new et.Element('plugin');
    el.attrib.name = attributes.name;
    if (attributes.spec) {
        el.attrib.spec = attributes.spec;
    }

    // support arbitrary object as variables source
    if (variables && typeof variables === 'object' && !Array.isArray(variables)) {
        variables = Object.keys(variables)
        .map(function (variableName) {
            return {name: variableName, value: variables[variableName]};
        });
    }

    if (variables) {
        variables.forEach(function (variable) {
            el.append(new et.Element('variable', { name: variable.name, value: variable.value }));
        });
    }
    this.doc.getroot().append(el);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cordova.cordova_lib.configparser.prototype.android_activityName"></a>[function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>android_activityName ()](#apidoc.element.cordova.cordova_lib.configparser.prototype.android_activityName)
- description and source-code
```javascript
android_activityName = function () {
    return this.getAttribute('android-activityName');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cordova.cordova_lib.configparser.prototype.android_packageName"></a>[function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>android_packageName ()](#apidoc.element.cordova.cordova_lib.configparser.prototype.android_packageName)
- description and source-code
```javascript
android_packageName = function () {
    return this.getAttribute('android-packageName');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cordova.cordova_lib.configparser.prototype.android_versionCode"></a>[function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>android_versionCode ()](#apidoc.element.cordova.cordova_lib.configparser.prototype.android_versionCode)
- description and source-code
```javascript
android_versionCode = function () {
    return this.getAttribute('android-versionCode');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cordova.cordova_lib.configparser.prototype.author"></a>[function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>author ()](#apidoc.element.cordova.cordova_lib.configparser.prototype.author)
- description and source-code
```javascript
author = function () {
    return getNodeTextSafe(this.doc.find('author'));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cordova.cordova_lib.configparser.prototype.description"></a>[function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>description ()](#apidoc.element.cordova.cordova_lib.configparser.prototype.description)
- description and source-code
```javascript
description = function () {
    return getNodeTextSafe(this.doc.find('description'));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cordova.cordova_lib.configparser.prototype.getAccesses"></a>[function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>getAccesses ()](#apidoc.element.cordova.cordova_lib.configparser.prototype.getAccesses)
- description and source-code
```javascript
getAccesses = function () {
    var accesses = this.doc.findall('./access');
    return accesses.map(function(access){
        var minimum_tls_version = access.attrib['minimum-tls-version'];<span class="apidocCodeCommentSpan"> /* String */
</span>        var requires_forward_secrecy = access.attrib['requires-forward-secrecy']; /* Boolean */
        var requires_certificate_transparency = access.attrib['requires-certificate-transparency']; /* Boolean */
        var allows_arbitrary_loads_in_web_content = access.attrib['allows-arbitrary-loads-in-web-content']; /* Boolean */
        var allows_arbitrary_loads_in_media = access.attrib['allows-arbitrary-loads-in-media']; /* Boolean */
        var allows_local_networking = access.attrib['allows-local-networking']; /* Boolean */

        return {
            'origin': access.attrib.origin,
            'minimum_tls_version': minimum_tls_version,
            'requires_forward_secrecy' : requires_forward_secrecy,
            'requires_certificate_transparency' : requires_certificate_transparency,
            'allows_arbitrary_loads_in_web_content' : allows_arbitrary_loads_in_web_content,
            'allows_arbitrary_loads_in_media' : allows_arbitrary_loads_in_media,
            'allows_local_networking' : allows_local_networking
        };
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cordova.cordova_lib.configparser.prototype.getAllowIntents"></a>[function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>getAllowIntents ()](#apidoc.element.cordova.cordova_lib.configparser.prototype.getAllowIntents)
- description and source-code
```javascript
getAllowIntents = function () {
    var allow_intents = this.doc.findall('./allow-intent');
    return allow_intents.map(function(allow_intent){
        return {
            'href': allow_intent.attrib.href
        };
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cordova.cordova_lib.configparser.prototype.getAllowNavigations"></a>[function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>getAllowNavigations ()](#apidoc.element.cordova.cordova_lib.configparser.prototype.getAllowNavigations)
- description and source-code
```javascript
getAllowNavigations = function () {
    var allow_navigations = this.doc.findall('./allow-navigation');
    return allow_navigations.map(function(allow_navigation){
        var minimum_tls_version = allow_navigation.attrib['minimum-tls-version'];<span class="apidocCodeCommentSpan"> /* String */
</span>        var requires_forward_secrecy = allow_navigation.attrib['requires-forward-secrecy']; /* Boolean */
        var requires_certificate_transparency = allow_navigation.attrib['requires-certificate-transparency']; /* Boolean */

        return {
            'href': allow_navigation.attrib.href,
            'minimum_tls_version': minimum_tls_version,
            'requires_forward_secrecy' : requires_forward_secrecy,
            'requires_certificate_transparency' : requires_certificate_transparency
        };
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cordova.cordova_lib.configparser.prototype.getAttribute"></a>[function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>getAttribute (attr)](#apidoc.element.cordova.cordova_lib.configparser.prototype.getAttribute)
- description and source-code
```javascript
getAttribute = function (attr) {
    return this.doc.getroot().attrib[attr];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cordova.cordova_lib.configparser.prototype.getEditConfigs"></a>[function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>getEditConfigs (platform)](#apidoc.element.cordova.cordova_lib.configparser.prototype.getEditConfigs)
- description and source-code
```javascript
getEditConfigs = function (platform) {
    var platform_tag = this.doc.find('./platform[@name="' + platform + '"]');
    var platform_edit_configs = platform_tag ? platform_tag.findall('edit-config') : [];

    var edit_configs = this.doc.findall('edit-config').concat(platform_edit_configs);

    return edit_configs.map(function(tag) {
        var editConfig =
            {
                file : tag.attrib['file'],
                target : tag.attrib['target'],
                mode : tag.attrib['mode'],
                id : 'config.xml',
                xmls : tag.getchildren()
            };
        return editConfig;
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cordova.cordova_lib.configparser.prototype.getEngines"></a>[function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>getEngines ()](#apidoc.element.cordova.cordova_lib.configparser.prototype.getEngines)
- description and source-code
```javascript
getEngines = function (){
    var engines = this.doc.findall('./engine');
    return engines.map(function(engine){
        var spec = engine.attrib.spec || engine.attrib.version;
        return {
            'name': engine.attrib.name,
            'spec': spec ? spec : null
        };
    });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cordova.cordova_lib.configparser.prototype.getFileResources"></a>[function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>getFileResources (platform)](#apidoc.element.cordova.cordova_lib.configparser.prototype.getFileResources)
- description and source-code
```javascript
getFileResources = function (platform) {
    var fileResources = [];

    if (platform) { // platform specific resources
        fileResources = this.doc.findall('platform[@name=\'' + platform + '\']/resource-file').map(function(tag) {
            return {
                platform: platform,
                src: tag.attrib.src,
                target: tag.attrib.target,
                versions: tag.attrib.versions,
                deviceTarget: tag.attrib['device-target'],
                arch: tag.attrib.arch
            };
        });
    }

    return fileResources;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cordova.cordova_lib.configparser.prototype.getGlobalPreference"></a>[function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>getGlobalPreference (name)](#apidoc.element.cordova.cordova_lib.configparser.prototype.getGlobalPreference)
- description and source-code
```javascript
getGlobalPreference = function (name) {
    return findElementAttributeValue(name, this.doc.findall('preference'));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cordova.cordova_lib.configparser.prototype.getHookScripts"></a>[function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>getHookScripts (hook, platforms)](#apidoc.element.cordova.cordova_lib.configparser.prototype.getHookScripts)
- description and source-code
```javascript
getHookScripts = function (hook, platforms) {
    var self = this;
    var scriptElements = self.doc.findall('./hook');

    if(platforms) {
        platforms.forEach(function (platform) {
            scriptElements = scriptElements.concat(self.doc.findall('./platform[@name="' + platform + '"]/hook'));
        });
    }

    function filterScriptByHookType(el) {
        return el.attrib.src && el.attrib.type && el.attrib.type.toLowerCase() === hook;
    }

    return scriptElements.filter(filterScriptByHookType);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cordova.cordova_lib.configparser.prototype.getIcons"></a>[function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>getIcons (platform)](#apidoc.element.cordova.cordova_lib.configparser.prototype.getIcons)
- description and source-code
```javascript
getIcons = function (platform) {
    return this.getStaticResources(platform, 'icon');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cordova.cordova_lib.configparser.prototype.getPlatformPreference"></a>[function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>getPlatformPreference (name, platform)](#apidoc.element.cordova.cordova_lib.configparser.prototype.getPlatformPreference)
- description and source-code
```javascript
getPlatformPreference = function (name, platform) {
    return findElementAttributeValue(name, this.doc.findall('platform[@name=\'' + platform + '\']/preference'));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cordova.cordova_lib.configparser.prototype.getPlugin"></a>[function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>getPlugin (id)](#apidoc.element.cordova.cordova_lib.configparser.prototype.getPlugin)
- description and source-code
```javascript
getPlugin = function (id){
    if(!id){
        return undefined;
    }
    var pluginElement = this.doc.find('./plugin/[@name="' + id + '"]');
    if (null === pluginElement) {
        var legacyFeature =  this.doc.find('./feature/param[@name="id"][@value="' + id + '"]/..');
        if(legacyFeature){
             events.emit('log', 'Found deprecated feature entry for ' + id +' in config.xml.');
            return featureToPlugin(legacyFeature);
        }
        return undefined;
    }
    var plugin = {};

    plugin.name = pluginElement.attrib.name;
    plugin.spec = pluginElement.attrib.spec || pluginElement.attrib.src || pluginElement.attrib.version;
    plugin.variables = {};
    var variableElements = pluginElement.findall('variable');
    variableElements.forEach(function(varElement){
        var name = varElement.attrib.name;
        var value = varElement.attrib.value;
        if(name){
            plugin.variables[name] = value;
        }
    });
    return plugin;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cordova.cordova_lib.configparser.prototype.getPluginIdList"></a>[function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>getPluginIdList ()](#apidoc.element.cordova.cordova_lib.configparser.prototype.getPluginIdList)
- description and source-code
```javascript
getPluginIdList = function () {
    var plugins = this.doc.findall('plugin');
    var result = plugins.map(function(plugin){
        return plugin.attrib.name;
    });
    var features = this.doc.findall('feature');
    features.forEach(function(element ){
        var idTag = element.find('./param[@name="id"]');
        if(idTag){
            result.push(idTag.attrib.value);
        }
    });
    return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cordova.cordova_lib.configparser.prototype.getPlugins"></a>[function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>getPlugins ()](#apidoc.element.cordova.cordova_lib.configparser.prototype.getPlugins)
- description and source-code
```javascript
getPlugins = function () {
    return this.getPluginIdList().map(function (pluginId) {
        return this.getPlugin(pluginId);
    }, this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cordova.cordova_lib.configparser.prototype.getPreference"></a>[function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>getPreference (name, platform)](#apidoc.element.cordova.cordova_lib.configparser.prototype.getPreference)
- description and source-code
```javascript
getPreference = function (name, platform) {

    var platformPreference = '';

    if (platform) {
        platformPreference = this.getPlatformPreference(name, platform);
    }

    return platformPreference ? platformPreference : this.getGlobalPreference(name);

}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cordova.cordova_lib.configparser.prototype.getSplashScreens"></a>[function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>getSplashScreens (platform)](#apidoc.element.cordova.cordova_lib.configparser.prototype.getSplashScreens)
- description and source-code
```javascript
getSplashScreens = function (platform) {
    return this.getStaticResources(platform, 'splash');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cordova.cordova_lib.configparser.prototype.getStaticResources"></a>[function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>getStaticResources (platform, resourceName)](#apidoc.element.cordova.cordova_lib.configparser.prototype.getStaticResources)
- description and source-code
```javascript
getStaticResources = function (platform, resourceName) {
    var ret = [],
        staticResources = [];
    if (platform) { // platform specific icons
        this.doc.findall('platform[@name=\'' + platform + '\']/' + resourceName).forEach(function(elt){
            elt.platform = platform; // mark as platform specific resource
            staticResources.push(elt);
        });
    }
    // root level resources
    staticResources = staticResources.concat(this.doc.findall(resourceName));
    // parse resource elements
    var that = this;
    staticResources.forEach(function (elt) {
        var res = {};
        res.src = elt.attrib.src;
        res.target = elt.attrib.target || undefined;
        res.density = elt.attrib['density'] || elt.attrib[that.cdvNamespacePrefix+':density'] || elt.attrib['gap:density'];
        res.platform = elt.platform || null; // null means icon represents default icon (shared between platforms)
        res.width = +elt.attrib.width || undefined;
        res.height = +elt.attrib.height || undefined;

        // default icon
        if (!res.width && !res.height && !res.density) {
            ret.defaultResource = res;
        }
        ret.push(res);
    });

<span class="apidocCodeCommentSpan">    /**
     * Returns resource with specified width and/or height.
     * @param  {number} width Width of resource.
     * @param  {number} height Height of resource.
     * @return {Resource} Resource object or null if not found.
     */
</span>    ret.getBySize = function(width, height) {
        return ret.filter(function(res) {
            if (!res.width && !res.height) {
                return false;
            }
            return ((!res.width || (width == res.width)) &&
                (!res.height || (height == res.height)));
        })[0] || null;
    };

    /**
     * Returns resource with specified density.
     * @param  {string} density Density of resource.
     * @return {Resource}       Resource object or null if not found.
     */
    ret.getByDensity = function(density) {
        return ret.filter(function(res) {
            return res.density == density;
        })[0] || null;
    };

    /** Returns default icons */
    ret.getDefault = function() {
        return ret.defaultResource;
    };

    return ret;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cordova.cordova_lib.configparser.prototype.ios_CFBundleIdentifier"></a>[function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>ios_CFBundleIdentifier ()](#apidoc.element.cordova.cordova_lib.configparser.prototype.ios_CFBundleIdentifier)
- description and source-code
```javascript
ios_CFBundleIdentifier = function () {
    return this.getAttribute('ios-CFBundleIdentifier');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cordova.cordova_lib.configparser.prototype.ios_CFBundleVersion"></a>[function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>ios_CFBundleVersion ()](#apidoc.element.cordova.cordova_lib.configparser.prototype.ios_CFBundleVersion)
- description and source-code
```javascript
ios_CFBundleVersion = function () {
    return this.getAttribute('ios-CFBundleVersion');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cordova.cordova_lib.configparser.prototype.name"></a>[function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>name ()](#apidoc.element.cordova.cordova_lib.configparser.prototype.name)
- description and source-code
```javascript
name = function () {
    return getNodeTextSafe(this.doc.find('name'));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cordova.cordova_lib.configparser.prototype.packageName"></a>[function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>packageName (id)](#apidoc.element.cordova.cordova_lib.configparser.prototype.packageName)
- description and source-code
```javascript
packageName = function (id) {
    return this.getAttribute('id');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cordova.cordova_lib.configparser.prototype.removeEngine"></a>[function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>removeEngine (name)](#apidoc.element.cordova.cordova_lib.configparser.prototype.removeEngine)
- description and source-code
```javascript
removeEngine = function (name){
    var engines = this.doc.findall('./engine/[@name="' +name+'"]');
    for(var i=0; i < engines.length; i++){
        var children = this.doc.getroot().getchildren();
        var idx = children.indexOf(engines[i]);
        if(idx > -1){
            children.splice(idx,1);
        }
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cordova.cordova_lib.configparser.prototype.removePlugin"></a>[function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>removePlugin (id)](#apidoc.element.cordova.cordova_lib.configparser.prototype.removePlugin)
- description and source-code
```javascript
removePlugin = function (id){
    if(id){
        var plugins = this.doc.findall('./plugin/[@name="' + id + '"]')
            .concat(this.doc.findall('./feature/param[@name="id"][@value="' + id + '"]/..'));
        var children = this.doc.getroot().getchildren();
        plugins.forEach(function (plugin) {
            var idx = children.indexOf(plugin);
            if (idx > -1) {
                children.splice(idx, 1);
            }
        });
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cordova.cordova_lib.configparser.prototype.setDescription"></a>[function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>setDescription (text)](#apidoc.element.cordova.cordova_lib.configparser.prototype.setDescription)
- description and source-code
```javascript
setDescription = function (text) {
    var el = findOrCreate(this.doc, 'description');
    el.text = text;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cordova.cordova_lib.configparser.prototype.setGlobalPreference"></a>[function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>setGlobalPreference (name, value)](#apidoc.element.cordova.cordova_lib.configparser.prototype.setGlobalPreference)
- description and source-code
```javascript
setGlobalPreference = function (name, value) {
    var pref = this.doc.find('preference[@name="' + name + '"]');
    if (!pref) {
        pref = new et.Element('preference');
        pref.attrib.name = name;
        this.doc.getroot().append(pref);
    }
    pref.attrib.value = value;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cordova.cordova_lib.configparser.prototype.setName"></a>[function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>setName (name)](#apidoc.element.cordova.cordova_lib.configparser.prototype.setName)
- description and source-code
```javascript
setName = function (name) {
    var el = findOrCreate(this.doc, 'name');
    el.text = name;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cordova.cordova_lib.configparser.prototype.setPackageName"></a>[function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>setPackageName (id)](#apidoc.element.cordova.cordova_lib.configparser.prototype.setPackageName)
- description and source-code
```javascript
setPackageName = function (id) {
    this.doc.getroot().attrib['id'] = id;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cordova.cordova_lib.configparser.prototype.setVersion"></a>[function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>setVersion (value)](#apidoc.element.cordova.cordova_lib.configparser.prototype.setVersion)
- description and source-code
```javascript
setVersion = function (value) {
    this.doc.getroot().attrib['version'] = value;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cordova.cordova_lib.configparser.prototype.version"></a>[function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>version ()](#apidoc.element.cordova.cordova_lib.configparser.prototype.version)
- description and source-code
```javascript
version = function () {
    return this.getAttribute('version');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cordova.cordova_lib.configparser.prototype.windows_packageVersion"></a>[function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>windows_packageVersion ()](#apidoc.element.cordova.cordova_lib.configparser.prototype.windows_packageVersion)
- description and source-code
```javascript
windows_packageVersion = function () {
    return this.getAttribute('windows-packageVersion');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cordova.cordova_lib.configparser.prototype.write"></a>[function <span class="apidocSignatureSpan">cordova.cordova_lib.configparser.prototype.</span>write ()](#apidoc.element.cordova.cordova_lib.configparser.prototype.write)
- description and source-code
```javascript
write = function () {
    fs.writeFileSync(this.path, this.doc.write({indent: 4}), 'utf-8');
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.cordova.cordova_lib.events"></a>[module cordova.cordova_lib.events](#apidoc.module.cordova.cordova_lib.events)

#### <a name="apidoc.element.cordova.cordova_lib.events.emit"></a>[function <span class="apidocSignatureSpan">cordova.cordova_lib.events.</span>emit ()](#apidoc.element.cordova.cordova_lib.events.emit)
- description and source-code
```javascript
emit = function () {

    var args = Array.prototype.slice.call(arguments);

    if (EVENTS_RECEIVER) {
        EVENTS_RECEIVER.emit.apply(EVENTS_RECEIVER, args);
    }

    return emit.apply(this, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.cordova.cordova_lib.events.forwardEventsTo"></a>[function <span class="apidocSignatureSpan">cordova.cordova_lib.events.</span>forwardEventsTo (eventEmitter)](#apidoc.element.cordova.cordova_lib.events.forwardEventsTo)
- description and source-code
```javascript
forwardEventsTo = function (eventEmitter) {

    // If no argument is specified disable events forwarding
    if (!eventEmitter) {
        EVENTS_RECEIVER = undefined;
        return;
    }

    if (!(eventEmitter instanceof EventEmitter))
        throw new Error('Cordova events can be redirected to another EventEmitter instance only');

    // CB-10940 Skipping forwarding to self to avoid infinite recursion.
    // This is the case when the modules are npm-linked.
    if (this !== eventEmitter) {
        EVENTS_RECEIVER = eventEmitter;
    } else {
        // Reset forwarding if we are subscribing to self
        EVENTS_RECEIVER = undefined;
    }
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
