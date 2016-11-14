# GeneratedRestClients
Hmmm trying this out

Ok, I'm playing a bit.... here's 2 swagger clients i generated.

<ol>
<li> 'petstore', i used this: https://github.com/swagger-api/swagger-codegen#to-generate-a-sample-client-library</li>
- to generate rest client API use the: petstore_swaggerclient  (edit with your own local path)

<li> my own 'https://github.com/jrpboy55/SpringBootWithSwaggerEnable' (see the 'initial' branch)</li>
- with mine, i have to edit the 'ModelAndView' as there's a couple of duplicate enums... weird
- and...the 'Principal' object in one of the Boot Health controllers is showing up as 'class not found'. I reimport it as a Spring Security 'Principal'..
- to generate rest client API use the: boot_swaggerclient (edit with your own local path)
</ol>
have to dig more...
