    <rdf:RDF xmlns:foaf="http://xmlns.com/foaf/0.1/" xmlns:owl="http://www.w3.org/2002/07/owl#"
             xmlns:rdfs="http://www.w3.org/2000/01/rdf-schema#"
             xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#"
             xmlns:dcat="http://www.w3.org/ns/dcat#"
             xmlns:ods="http://open-data-standards.github.com/2012/01/open-data-standards#"
             xmlns:dct="http://purl.org/dc/terms/">


        <dcat:Dataset rdf:about="https://fda.demo.socrata.com/dataset/Shell-Eggs-Recall-List2010/hnup-s94r">
            <owl:sameAs rdf:resource="https://fda.demo.socrata.com/resource/hnup-s94r"></owl:sameAs>
            <dct:title>Shell Eggs Recall List2010</dct:title>
            <dct:description>List of all the recalled egg products from 2010</dct:description>
            <dct:identifier>hnup-s94r</dct:identifier>
            <dcat:keyword>FDA</dcat:keyword>

            <ods:api>
                <dct:title>SODA Api for Current Recalls</dct:title>
                <dct:description>This is the SODA Api for getting access to all the egg products that are actively being investigated</dct:description>
                <dct:identifier>ongoing-egg-recalls</dct:identifier>
                <dcat:accessURL>https://fda.demo.socrata.com/resource/ongoing-egg-recalls</dcat:accessURL>
                <dcat:keyword>Eggs</dcat:keyword>
                <dcat:keyword>Recalls</dcat:keyword>

                <ods:authentication>Basic</ods:authentication>
                <ods:documentation>https://fda.demo.socrata.com/developers/docs/egg-recalls</ods:documentation>
                <ods:client_library>https://github.com/socrata/soda-java</ods:client_library>
                <ods:client_library>https://github.com/socrata/socrata-python</ods:client_library>
                <ods:client_library>https://github.com/socrata/socrata-api-csharp</ods:client_library>

                <ods:contact_email>someone@fda.gov</ods:contact_email>

                <!-- MIME Types provided -->
                <dct:format>application/json</dct:format>
                <dct:format>application/rdf+xml</dct:format>
                <dct:format>text/csv</dct:format>

                <!-- What type of API it is -->
                <ods:api_type>rest/soda</ods:api_type>
                <ods:last_modified>2012-10-10T16:46:00+800</ods:last_modified>
                <ods:created>2012-10-10T16:46:00+800</ods:created>
            </ods:api>
            <ods:api>
                <dct:title>SODA Api for Aggregated Recalls Per Brand Name</dct:title>
                <dct:description>This API is an aggregation built on the egg recalls that keeps track of the number of
                recalls for each brand name.</dct:description>
                <dct:identifier>ongoing-egg-recalls-by-brand</dct:identifier>
                <dcat:accessURL>https://fda.demo.socrata.com/resource/ongoing-egg-recalls-by-brand</dcat:accessURL>
                <dcat:keyword>Eggs</dcat:keyword>
                <dcat:keyword>Recalls</dcat:keyword>
                <dcat:keyword>Brands</dcat:keyword>

                <ods:documentation>https://fda.demo.socrata.com/developers/docs/ongoing-egg-recalls-by-brand</ods:documentation>
                <ods:client_library>https://github.com/socrata/soda-java</ods:client_library>
                <ods:client_library>https://github.com/socrata/socrata-python</ods:client_library>
                <ods:client_library>https://github.com/socrata/socrata-api-csharp</ods:client_library>

                <ods:contact_email>someone@fda.gov</ods:contact_email>

                <!-- MIME Types provided -->
                <dct:format>application/json</dct:format>
                <dct:format>application/rdf+xml</dct:format>
                <dct:format>text/csv</dct:format>

                <!-- What type of API it is -->
                <ods:api_type>rest/soda</ods:api_type>
                <ods:last_modified>2012-10-10T16:46:00+800</ods:last_modified>
                <ods:created>2012-10-10T16:46:00+800</ods:created>
            </ods:api>
            <ods:chart>
                <dct:title>Recalls by date</dct:title>
                <dct:description>A line graph built to show the number of recalls by date.</dct:description>
                <dct:identifier>a9z2-ddre</dct:identifier>
                <dcat:accessURL>https://fda.demo.socrata.com/dataset/Recalls-By-date/a9z2-ddre</dcat:accessURL>
                <dct:format>text/html</dct:format>
            </ods:chart>
        </dcat:Dataset>


        <dcat:Dataset rdf:about="https://fda.demo.socrata.com/dataset/Registered-Drug-Dispensaries/xyqn-j4yg">
            <owl:sameAs rdf:resource="https://fda.demo.socrata.com/resource/xyqn-j4yg"></owl:sameAs>
            <dct:title>Registered Drug Dispensaries</dct:title>
            <dct:description>The Drug Listing Act of 1972 requires registered drug establishments to provide the Food and
            Drug Administration (FDA) with a current list of all drugs manufactured, prepared, propagated, compounded, or
            processed by it for commercial distribution. (See Section 510 of the Federal Food, Drug, and Cosmetic Act (Act)
            (21 U.S.C. § 360)). Drug products are identified and reported using a unique, three-segment number, called the
            National Drug Code (NDC), which is a universal product identifier for human drugs. FDA inputs the full NDC number
            and the information submitted as part of the listing process into a database known as the Drug Registration and
            Listing System (DRLS). On the 1st and 15th of each month, FDA extracts some of the information from the DRLS data
            base (currently, properly listed marketed prescription drug products and insulin) and publishes that information in
            the NDC Directory.</dct:description>

            <dct:identifier>xyqn-j4yg</dct:identifier>
            <dcat:keyword>FDA</dcat:keyword>

            <ods:api>
                <dct:title>SODA Api for Drug Dispensaries</dct:title>
                <dct:description>This is the SODA Api for getting access to the Drug Dispensaries</dct:description>
                <dct:identifier>drug-dispensaries</dct:identifier>
                <dcat:accessURL>https://fda.demo.socrata.com/resource/drug-dispensaries</dcat:accessURL>
                <dcat:keyword>Dispensaries</dcat:keyword>

                <ods:documentation>https://fda.demo.socrata.com/developers/docs/drug-dispensaries</ods:documentation>
                <ods:client_library>https://github.com/socrata/soda-java</ods:client_library>
                <ods:client_library>https://github.com/socrata/socrata-python</ods:client_library>
                <ods:client_library>https://github.com/socrata/socrata-api-csharp</ods:client_library>

                <ods:contact_email>someone@fda.gov</ods:contact_email>

                <!-- MIME Types provided -->
                <dct:format>application/json</dct:format>
                <dct:format>application/rdf+xml</dct:format>
                <dct:format>text/csv</dct:format>

                <!-- What type of API it is -->
                <ods:api_type>rest/soda</ods:api_type>
                <ods:last_modified>2012-10-10T16:46:00+800</ods:last_modified>
                <ods:created>2012-10-10T16:46:00+800</ods:created>
            </ods:api>
            <ods:map>
                <dct:title>Maryland Drug Dispensaries</dct:title>
                <dct:description>A map with all the Maryland Drug Dispensaries on it.</dct:description>
                <dct:identifier>fkyd-by4c</dct:identifier>
                <dcat:accessURL>https://fda.demo.socrata.com/dataset/Maryland-Drug-Dispensaries/fkyd-by4c</dcat:accessURL>
                <dct:format>text/html</dct:format>
            </ods:map>
        </dcat:Dataset>

    </rdf>