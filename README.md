# Home Assistant Configuration by [Landrash]
[Home Assistant] configuration files (YAMLs)

This is my Home Assistant Configuration. These configurations are heavily inspired by others like [Dale3h] and [CCOSTAN].

Our current setup consists of Home Assistant running on a Raspberry Pi 3 using [Hassbian].
The configuration is highly modular and should be easily reusable since it's split up in [packages].
Most 'hosts', 'ip-addresses', 'api-keys' and similar are stored in a [secrets].yaml file and not contained in this repository.

## **Hassbian**
A few software suites from [Hassbian] are used:
 * [Duckdns] with Lets Encrypt certificate.
 * [Mosquitto] with external brooker [CloudMQTT] for use with [Owntracks].

## **Hardware in Use:**
 * 1x [Chromecast] 1st genration
 * 1x [Chromecast] 2nd generation
 * 1x IKEA [Trådfri Gateway]
 * 3x IKEA [Trådfri Motion] Detector
 * 3x IKEA [Trådfri Remote]
 * 12x IKEA [Trådfri Light]
 * 2x [OpenMQTTGateway]

## **Screenshots of views**
![Home Tab](images/home.png?raw=true "Home")
![Family Tab](images/family.png?raw=true "Family")
![Network Tab](images/network.png?raw=true "Network")
![Sensors Tab](images/sensors.png?raw=true "Sensors")
![Media Players Tab](images/mediaplayers.png?raw=true "Media Players")
![Automation Tab](images/automation.png?raw=true "Automation")
![Weather Tab](images/weather.png?raw=true "Weather")

[Home Assistant]:https://home-assistant.io/
[Landrash]:https://github.com/Landrash
[CCOSTAN]:https://github.com/CCOSTAN/Home-AssistantConfig
[Dale3h]:https://github.com/dale3h/homeassistant-config/
[Hassbian]:https://github.com/home-assistant/hassbian-scripts
[packages]:https://www.home-assistant.io/docs/configuration/packages/
[secrets]:https://www.home-assistant.io/docs/configuration/secrets/
[Duckdns]:https://github.com/home-assistant/hassbian-scripts/blob/dev/docs/duckdns.md
[Mosquitto]:https://mosquitto.org/
[CloudMQTT]:https://www.cloudmqtt.com/
[Owntracks]:https://www.home-assistant.io/components/device_tracker.owntracks/
[Chromecast]:https://en.wikipedia.org/wiki/Chromecast
[Trådfri Gateway]:https://www.ikea.com/se/sv/catalog/products/40337806/
[Trådfri Motion]:https://www.ikea.com/se/sv/catalog/products/30383511/
[Trådfri Remote]:https://www.ikea.com/se/sv/catalog/products/30338849/
[Trådfri Light]:https://www.ikea.com/se/sv/catalog/products/10318263/
[OpenMQTTGateway]:https://github.com/1technophile/OpenMQTTGateway
