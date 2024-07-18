The open source of knowledge is one of the requirements that humans will reach in the not too distant future. No knowledge can be monopolized by a person or company or governments for a long time and be used against people and for personal gain, because our knowledge is an achievement of several hundred thousand years or maybe several million years that has evolved in a social process. Inherited to us, something called the ownership of knowledge and its monopoly becomes a form of human exploitation. This is a library of all free and open source projects that make people look more aware of their lives and more consciously shape more just and developed societies in the future.

Die offene Quelle des Wissens ist eine der Anforderungen, die die Menschen in naher Zukunft erreichen werden. Kein Wissen kann von einer Person, einem Unternehmen oder Regierungen lange monopolisiert und gegen Menschen verwendet werden, um persönlichen Gewinn zu erzielen, denn unser Wissen ist eine Errungenschaft von mehreren hunderttausend Jahren oder vielleicht mehreren Millionen Jahren, die sich in einem sozialen Prozess entwickelt hat. An uns vererbt, wird etwas namens Eigentum am Wissen und sein Monopol zu einer Form der menschlichen Ausbeutung. Dies ist eine Bibliothek aller freien und Open-Source-Projekte, die dazu beitragen, dass Menschen sich bewusster über ihr Leben werden und bewusster formen, um in Zukunft gerechtere und entwickeltere Gesellschaften zu schaffen.

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            font-family: Arial, sans-serif;
        }
        table {
            width: 100%;
            border-collapse: collapse;
        }
        th, td {
            padding: 8px 12px;
            border: 1px solid #ddd;
            text-align: left;
            transition: background-color 0.3s ease;
        }
        th {
            cursor: pointer;
            background-color: #f4f4f4;
            position: relative;
        }
        th.sorted-asc::after, th.sorted-desc::after {
            content: '';
            position: absolute;
            right: 8px;
            width: 0; 
            height: 0; 
        }
        th.sorted-asc::after {
            border-left: 5px solid transparent;
            border-right: 5px solid transparent;
            border-bottom: 6px solid #000;
            top: 50%;
            transform: translateY(-50%);
        }
        th.sorted-desc::after {
            border-left: 5px solid transparent;
            border-right: 5px solid transparent;
            border-top: 6px solid #000;
            top: 50%;
            transform: translateY(-50%);
        }
        tr:hover {
            background-color: #f1f1f1;
        }
        .search-container {
            margin-bottom: 10px;
        }
        .search-box {
            padding: 8px;
            width: 100%;
            box-sizing: border-box;
        }
    </style>
    <title>Open Source Resources</title>
</head>
<body>

<div class="search-container">
    <input type="text" id="searchBox" class="search-box" placeholder="Search...">
</div>

<table id="interactiveTable">
    <thead>
        <tr>
            <th onclick="sortTable(0)">Name</th>
            <th onclick="sortTable(1)">Link</th>
        </tr>
    </thead>
    <tbody>
        <tr><td>Open Culture</td><td><a href="https://www.openculture.com/">https://www.openculture.com/</a></td></tr>
        <tr><td>Open Library</td><td><a href="https://openlibrary.org/">https://openlibrary.org/</a></td></tr>
        <tr><td>Open Access Journals</td><td><a href="https://oad.simmons.edu/oadwiki/Main_Page">https://oad.simmons.edu/oadwiki/Main_Page</a></td></tr>
        <tr><td>Open Education</td><td><a href="https://www.openeducation.net/">https://www.openeducation.net/</a></td></tr>
        <tr><td>Open Space</td><td><a href="https://www.openspaceweb.com/">https://www.openspaceweb.com/</a></td></tr>
        <tr><td>Open Source Textbooks</td><td><a href="http://open.umn.edu/opentextbooks/">http://open.umn.edu/opentextbooks/</a></td></tr>
        <tr><td>Open Textbooks Library</td><td><a href="https://open.library.umn.edu/subjects/14">https://open.library.umn.edu/subjects/14</a></td></tr>
        <tr><td>Open TextBookStore</td><td><a href="https://github.com/open-source-society/open-textbook-store">https://github.com/open-source-society/open-textbook-store</a></td></tr>
        <tr><td>OpenBookPublishers</td><td><a href="https://www.openbookpublishers.com/section/41/1">https://www.openbookpublishers.com/section/41/1</a></td></tr>
        <tr><td>OpenCritic</td><td><a href="https://www.opencritic.com/">https://www.opencritic.com/</a></td></tr>
        <tr><td>Oxford Scholarship Online</td><td><a href="https://www.oxfordscholarship.com/">https://www.oxfordscholarship.com/</a></td></tr>
        <tr><td>Pdfdrive</td><td><a href="https://www.pdfdrive.com/">https://www.pdfdrive.com/</a></td></tr>
        <tr><td>PhilPapers</td><td><a href="https://philpapers.org/">https://philpapers.org/</a></td></tr>
        <tr><td>Pltfrm</td><td><a href="https://www.pltfrm.org/">https://www.pltfrm.org/</a></td></tr>
        <tr><td>Politics and Prose</td><td><a href="https://www.politics-prose.com/bookstore">https://www.politics-prose.com/bookstore</a></td></tr>
        <tr><td>Project Gutenberg</td><td><a href="https://www.gutenberg.org/wiki/Main_Page">https://www.gutenberg.org/wiki/Main_Page</a></td></tr>
        <tr><td>Project Euclid</td><td><a href="https://projecteuclid.org/">https://projecteuclid.org/</a></td></tr>
        <tr><td>Public Domain Torrents</td><td><a href="https://www.publicdomaintorrents.info/">https://www.publicdomaintorrents.info/</a></td></tr>
        <tr><td>Public Health</td><td><a href="https://www.publichealth.hscni.net/">https://www.publichealth.hscni.net/</a></td></tr>
        <tr><td>Public Knowledge Project</td><td><a href="https://pkp.sfu.ca/">https://pkp.sfu.ca/</a></td></tr>
        <tr><td>PublicResource</td><td><a href="https://publicresource.org/">https://publicresource.org/</a></td></tr>
        <tr><td>Reddit PhD</td><td><a href="https://www.reddit.com/r/PhD/">https://www.reddit.com/r/PhD/</a></td></tr>
        <tr><td>Reason</td><td><a href="https://reason.com/">https://reason.com/</a></td></tr>
        <tr><td>ResourcED</td><td><a href="https://resources.educator%C4%80made.com/browse/">https://resources.educator%C4%80made.com/browse/</a></td></tr>
        <tr><td>RoyRosenzweigCenter</td><td><a href="https://www.roosevelthouse.hunter.cuny.edu/">https://www.roosevelthouse.hunter.cuny.edu/</a></td></tr>
        <tr><td>Science Press</td><td><a href="https://sciencepress.com/">https://sciencepress.com/</a></td></tr>
        <tr><td>Saylor Academy</td><td><a href="https://www.saylor.org/">https://www.saylor.org/</a></td></tr>
        <tr><td>Scholarpedia</td><td><a href="https://www.scholarpedia.org/">https://www.scholarpedia.org/</a></td></tr>
        <tr><td>SlideShare</td><td><a href="https://www.slideshare.net/search/slideshow">https://www.slideshare.net/search/slideshow</a></td></tr>
        <tr><td>Smashwords</td><td><a href="https://www.smashwords.com/">https://www.smashwords.com/</a></td></tr>
        <tr><td>SoftArchive</td><td><a href="https://softarchive.net/">https://softarchive.net/</a></td></tr>
        <tr><td>SOPHIA</td><td><a href="https://www.sophia.org/">https://www.sophia.org/</a></td></tr>
        <tr><td>Sociological Abstracts</td><td><a href="https://www.proquest.com/products-services/Sociological-Abstracts.html">https://www.proquest.com/products-services/Sociological-Abstracts.html</a></td></tr>
        <tr><td>Soundcloud</td><td><a href="https://soundcloud.com/">https://soundcloud.com/</a></td></tr>
        <tr><td>Standard Ebooks</td><td><a href="https://standardebooks.org/">https://standardebooks.org/</a></td></tr>
        <tr><td>Stanford Encyclopedia of Philosophy</td><td><a href="https://plato.stanford.edu/">https://plato.stanford.edu/</a></td></tr>
        <tr><td>Stanford Literature</td><td><a href="https://explorelit.org/">https://explorelit.org/</a></td></tr>
        <tr><td>Stoic</td><td><a href="https://www.stoicserenity.com/">https://www.stoicserenity.com/</a></td></tr>
        <tr><td>Textbook Revolution</td><td><a href="https://open.umn.edu/opentextbooks/">https://open.umn.edu/opentextbooks/</a></td></tr>
        <tr><td>The Anthropic</td><td><a href="https://www.anthropic.com/">https://www.anthropic.com/</a></td></tr>
        <tr><td>The Internet Classics Archive</td><td><a href="http://classics.mit.edu/">http://classics.mit.edu/</a></td></tr>
        <tr><td>The Literature Network</td><td><a href="https://www.online-literature.com/">https://www.online-literature.com/</a></td></tr>
        <tr><td>The Public Domain Review</td><td><a href="https://publicdomainreview.org/">https://publicdomainreview.org/</a></td></tr>
        <tr><td>TraditionalMountaineering</td><td><a href="http://traditionalmountaineering.org/">http://traditionalmountaineering.org/</a></td></tr>
        <tr><td>Ubiquity Press</td><td><a href="https://www.ubiquitypress.com/">https://www.ubiquitypress.com/</a></td></tr>
        <tr><td>Udacity</td><td><a href="https://www.udacity.com/">https://www.udacity.com/</a></td></tr>
        <tr><td>Unicorn</td><td><a href="https://www.unicornriot.ninja/">https://www.unicornriot.ninja/</a></td></tr>
        <tr><td>UniversityComic</td><td><a href="http://universitycomic.com/">http://universitycomic.com/</a></td></tr>
        <tr><td>Wattpad</td><td><a href="https://www.wattpad.com/">https://www.wattpad.com/</a></td></tr>
        <tr><td>Wikibooks</td><td><a href="https://en.wikibooks.org/wiki/Main_Page">https://en.wikibooks.org/wiki/Main_Page</a></td></tr>
        <tr><td>Wikimedia</td><td><a href="https://www.wikimediafoundation.org/our-work/">https://www.wikimediafoundation.org/our-work/</a></td></tr>
        <tr><td>Wikipedia</td><td><a href="https://en.wikipedia.org/wiki/Main_Page">https://en.wikipedia.org/wiki/Main_Page</a></td></tr>
        <tr><td>WikiSource</td><td><a href="https://en.wikisource.org/wiki/Main_Page">https://en.wikisource.org/wiki/Main_Page</a></td></tr>
        <tr><td>Yale Open Courses</td><td><a href="https://oyc.yale.edu/">https://oyc.yale.edu/</a></td></tr>
        <tr><td>Yewno</td><td><a href="https://www.yewno.com/">https://www.yewno.com/</a></td></tr>
        <tr><td>Z-Library</td><td><a href="https://b-ok.cc/">https://b-ok.cc/</a></td></tr>
    </tbody>
</table>

<script>
    document.getElementById('searchBox').addEventListener('keyup', function() {
        var filter = this.value.toUpperCase();
        var rows = document.querySelector("#interactiveTable tbody").rows;
        
        for (var i = 0; i < rows.length; i++) {
            var cells = rows[i].cells;
            var match = false;
            for (var j = 0; j < cells.length; j++) {
                if (cells[j].innerHTML.toUpperCase().indexOf(filter) > -1) {
                    match = true;
                    break;
                }
            }
            rows[i].style.display = match ? "" : "none";
        }
    });

    function sortTable(n) {
        var table = document.getElementById("interactiveTable");
        var rows = table.rows;
        var switching = true;
        var shouldSwitch;
        var direction = "asc"; 
        var switchcount = 0;

        // Remove sorted class from all headers
        var headers = table.querySelectorAll("th");
        headers.forEach(header => header.classList.remove("sorted-asc", "sorted-desc"));

        while (switching) {
            switching = false;
            var rowsArray = Array.from(rows).slice(1);

            for (var i = 0; i < rowsArray.length - 1; i++) {
                shouldSwitch = false;
                var x = rowsArray[i].getElementsByTagName("TD")[n];
                var y = rowsArray[i + 1].getElementsByTagName("TD")[n];

                if (direction == "asc") {
                    if (x.innerHTML.toLowerCase() > y.innerHTML.toLowerCase()) {
                        shouldSwitch = true;
                        break;
                    }
                } else if (direction == "desc") {
                    if (x.innerHTML.toLowerCase() < y.innerHTML.toLowerCase()) {
                        shouldSwitch = true;
                        break;
                    }
                }
            }
            if (shouldSwitch) {
                rowsArray[i].parentNode.insertBefore(rowsArray[i + 1], rowsArray[i]);
                switching = true;
                switchcount++;
            } else {
                if (switchcount == 0 && direction == "asc") {
                    direction = "desc";
                    switching = true;
                }
            }
        }

        // Add sorted class to the sorted header
        if (direction == "asc") {
            headers[n].classList.add("sorted-asc");
        } else {
            headers[n].classList.add("sorted-desc");
        }
    }
</script>

</body>
</html>
